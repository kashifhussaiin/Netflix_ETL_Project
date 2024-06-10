# Netflix_ETL_Project
Netflix data cleaning and analysis (SQL+PYTHON): A ELT project where we ingest raw data into sql using python and do data cleaning and data modelling interview SQL and then answering some questions on the Netflix dataset.

## Overview

The goal of this ETL project would be to extract this data, perform necessary transformations to clean and organize it, and then load it into a PostgreSQL database. This will enable further analysis and insights into the content available on Netflix, such as understanding trends, popular genres, top-rated shows, and more.

## Dataset

About this Dataset: Netflix is one of the most popular media and video streaming platforms. They have over 8000 movies or tv shows available on their platform, as of mid-2021, they have over 200M Subscribers globally. This tabular dataset consists of listings of all the movies and tv shows available on Netflix, along with details such as - cast, directors, ratings, release year, duration, etc.

## Tools and Technologies Used

- Python
- Pandas
- PostgreSQL
- pgAdmin
- Miniconda 

## Project Structure

- `data/`: Directory for storing datasets.
- `notebook/`: Jupyter Notebooks for data exploration, cleaning, and analysis.
- `requirements.txt`: File containing the list of dependencies for the project.
- `README.md`: This file, containing information about the project.

## Setup

Got it. If you're using a Conda environment set up from a `requirements.txt` file and editing notebooks in VS Code with the kernel of that Conda environment, here are the corrected setup steps:

1. **Clone the Repository**: Clone the project repository from GitHub to your local machine.

```bash
git clone https://github.com/kashifhussaiin/Netflix_ETL_Project.git
```

2. **Navigate to the Project Directory**: Change your current directory to the project directory.

```bash
cd /Netflix_ETL_Project
```

3. **Create and Activate the Conda Environment**: Create a new Conda environment and activate it using the `requirements.txt` file.

```bash
conda create --name my_environment_name --file requirements.txt
conda activate my_environment_name
```

Replace `my_environment_name` with the name you want to give to your Conda environment.

4. **Start PostgreSQL**: Ensure that PostgreSQL is installed and running on your machine. If not, install PostgreSQL and start the PostgreSQL service.

5. **Start pgAdmin**: Open pgAdmin and connect to your PostgreSQL server. If pgAdmin is not installed, follow the instructions to install it.

6. **Create a Database**: Create a new database in PostgreSQL using pgAdmin or the command-line interface. You can name it `netflix_data_cleaning` or any other suitable name.

7. **Run Jupyter Notebooks in VS Code**: Open VS Code and navigate to the `notebook` directory within your project. Open the Jupyter notebook you want to work on.

8. **Select the Conda Environment Kernel**: In the Jupyter notebook, select the kernel corresponding to the Conda environment you created earlier (`my_environment_name`).

9. **Execute the Notebook Cells**: Run the cells in the Jupyter notebook to execute the ETL process. This will extract, transform, and load the Netflix dataset into your PostgreSQL database.

10. **Verify the Data**: Once the ETL process is complete, verify that the data has been successfully loaded into the PostgreSQL database using pgAdmin or by running SQL queries directly.

11. **Explore and Analyze**: Now that the data is loaded into the database, you can explore and analyze it further using SQL queries, visualization tools, or any other analytical techniques.

These steps should help you set up your project environment and start working on the ETL process for the Netflix dataset using VS Code and Jupyter notebooks with your Conda environment. Adjust the instructions as needed based on your specific project setup and requirements.


## Contributors

- [kashif hussain](https://github.com/kashifhussaiin)


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


## Acknowledgements

[If you've used any external resources, libraries, or datasets, acknowledge them here.]

## Contact

If you have any questions or suggestions, feel free to reach out:

- GitHub: [kashifhussaiin](https://github.com/kashifhussaiin)
- Email: kashifhussain.fj@gmail.com

