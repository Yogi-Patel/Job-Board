# Job-Board

## Installation

To run the Django Job Board on your local machine, follow these installation steps:

1. Clone the repository to your local machine:

   ```shell
   git clone <repository_url>
   ```

2. Navigate to the project directory:  
   ```shell
   cd Job-Board
   ```
3. Create a virtual environment (optional but recommended):  
   ```shell
   python -m venv env
   source env/bin/activate   
   # On Windows, use   
   env\Scripts\activate
   ```
4. Install the required dependencies:  
   ```shell
   pip install -r requirements.txt
   ```
5. Migrate the database:  
   ```shell
   python manage.py migrate
   ```
6. Create a superuser account to access the admin panel:  
   ```shell
   python manage.py createsuperuser
   ```
7. Start the development server:  
   ```shell
   python manage.py runserver
   ```

The application should now be running locally at http://localhost:8000.


*This README was generated by ChatGPT.*