## House Issue Tracker
My new house's todo.txt

## CLI Interface
To create an issue from the command line, simply:

    curl --user "cameronbriar:password" --request POST --data '{"title" : "Shampoo the carpets", "body" : "Rent a RugDoctor and clean the filthy, blue carpets", "labels" : ["interior", "contingent"] }' https://api.github.com/repos/cameronbriar/house/issues
