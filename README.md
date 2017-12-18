# JavaLogger
Very amazing logger which creates a logger which can be used to log loggable things. Creates files in a folder which you can select yourself!


## Usage
To start using the file, instantiate it like so:
```JAVA 
Logger logger = new Logger("Name", Level.ALL, Level.SEVERE);
```
The `Level.ALL` indicates which levels should be written to the file.   
The `Level.SEVERE` indicates which levels should be written to console.  

After setting up the logger, you can log new entries like so:  
```JAVA
catch (Exception e) {
    logger.log(Level.WARNING, e.getMessage());
}
```
