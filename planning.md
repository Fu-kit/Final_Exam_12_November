FUNCTION load_data():
    TRY:
        Load 'budget.csv' into a variable called 'df' using pandas.
    EXCEPT FileNotFoundError:
        PRINT "budget.csv not found. Creating a new budget."
        Create a new, empty pandas DataFrame 'df' with columns:
            ['date', 'description', 'type', 'amount']
    RETURN 'df'

