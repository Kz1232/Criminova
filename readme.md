## Follow the steps below to Install the project and run
    ###Downlaod the whole repo 
    ###Create virtual environment
    > command : 
    ''' py -m venv env '''
    ###Activate the virutal environment:
    >commnad :
    ''' env\Scripts\activate'''
    ### Install the files at requirements.txt:
    ''' pip install -r requirements.txt '''
    ### Create a database using the dumpfile :
    >    copy the dumpfile into the postgresql/16/bin folder
    ####open cmd in that folder and restore dump file:
    ''' psql -U postgres -d databasename -f crimenetx.sql '''
    #### replace the name of databse and user and password in database.py 
    #### Create the superuser using Newsuperuser.py 
    > Use replace the username and password in the file that is test as you desire
    ''' py Newsuperuser.py '''
    ###Run the cnova file and check the project.
    