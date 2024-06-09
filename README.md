# Step 1: Navigate to  project directory
cd address_book

# Step 2: Create a virtual environment
python -m venv myenv

# Step 3: Activate the virtual environment
myenv\Scripts\activate

# Step 4: Install the required packages
pip install fastapi uvicorn sqlalchemy databases pydantic geopy

# Step 5: Run the FastAPI application
uvicorn main:app --reload



### Code Files

Here’s a quick reference to the contents of each file:

- `main.py`: Contains the FastAPI application and route definitions.
- `models.py`: Defines the SQLAlchemy models.
- `database.py`: Sets up the database connection and session.
- `schemas.py`: Defines the Pydantic models for request and response validation.
- `crud.py`: Contains the CRUD operation functions.

