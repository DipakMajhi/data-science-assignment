# Read this first

## Data Science Assignment

You are required to perform the following tasks in the assignment:

1. Access the data from the DB by connecting to the database at the following location:
    - Host: `52.66.79.237`. Port: `3306`
    - The database credentials will be sent to you separately.
2. Read in the datasets. Use the [data_dictionary.md](data_dictionary.md) file to understand what each field means.
3. Perform data preprocessing and exploratory analysis of the data
4. You are required to join the appropriate tables, (wherever required) and process the following metrics -
    - The average number of plans sold per week.
    - The brand (`BrandID`) with the highest number of plans bought by customers.
    - The percentage of service requests raised under a plan of the total number of requests raised.
    - Use Python or R to perform the analysis (we prefer Python)
5. Visualize the data
6. For extra credit, predict the following:
    - Number of consumers who will join in the months of Nov-17, Dec-17 and Jan-18 for the given dataset
    - The probability that a Service Request will originate against a Sold Plan.
7. Document the following things:
    - Your thought process while working on this assignment.
    - The actual code. Ideally, we should be able to deploy this as-is.
8. Share the code and documentation  as a private gitlab or github repo.
9. You have 4 days to complete the assignment.
10. You can raise any questions you have in the issues on the github repo. Also check closed issues on the repo before you ask questions.

-----

Notes:

- This is a simulated dataset that we run on our test bench.
- Do keep in mind, that while we would like you to complete the entire assignment sometimes, you might not be able to finish in time. In such a case, your thought process becomes even more important. So don't worry too much about not completing in time.
- The server is intentionally low powered, so you will have to figure out how to work under that constraint.