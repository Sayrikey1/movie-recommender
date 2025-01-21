# Django-Based Movie Recommendation System

Welcome to the Django-Based Movie Recommendation System repository! This project is a web application that provides personalized movie recommendations to users based on their preferences and interaction history.

## Features
- **User Authentication**: Users can register, log in, and manage their profiles.
- **Movie Database**: Access a vast database of movies with details such as genre, cast, director, and release date.
- **Personalized Recommendations**: Generate movie recommendations tailored to each user's taste.
- **Interactive Interface**: Users can rate movies, view recommendations, and search for specific titles.

## Prerequisites
To run this project, ensure you have the following installed on your machine:

- Python (3.8 or higher)
- Django (4.0 or higher)
- PostgreSQL (or another supported database system)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/movie-recommendation-system.git
   ```

2. Navigate to the project directory:
   ```bash
   cd movie-recommendation-system
   ```

3. Create and activate a virtual environment:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
   ```

4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

5. Configure the database:
   - Update the `DATABASES` settings in `settings.py` with your database credentials.

6. Apply migrations:
   ```bash
   python manage.py migrate
   ```

7. Load initial movie data (see commands below).

8. Run the development server:
   ```bash
   python manage.py runserver
   ```

## Django Management Commands
This project includes custom Django management commands to streamline setup and recommendation processes:

### `load_movies`
Loads movie data into the database from a predefined dataset.

**Usage:**
```bash
python manage.py load_movies
```

### `make_recommendations`
Generates personalized movie recommendations for all users based on their ratings and preferences.

**Usage:**
```bash
python manage.py make_recommendations
```

## Usage
1. Register a new account or log in with an existing account.
2. Browse and search for movies to rate.
3. View your personalized movie recommendations on the dashboard.

## Contributing
We welcome contributions to improve this project! Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add your message here"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a pull request on GitHub.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact
For questions or suggestions, feel free to contact the repository owner:

- **Name**: Kamal Seriki
- **Email**: kamalseriki49@gmail.com
- **GitHub**: [Sayrikey1](https://github.com/your-username)

