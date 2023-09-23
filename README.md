# Criminal Intent

Created by: **Ryan Speese**

Reference: Adapted from Big Nerd Ranch's Android Programming Book (4th Edition)

## Summary

**Criminal Intent** is an android app that allows employees working in an office to report various "office crimes" in the hopes to catch who committed 
the act and bring justice and peace back to their workplace. Users can scroll through all the previously identified crimes, add a new crime, and update a
crime's details.

## Application Features

- Single activity architecture (one activity and multiple fragments) with fragment navigation and argument passing
- RecyclerView for list of crimes
- ConstraintLayout for individual crimes
- Room library for the database holding the crimes (uses the Repository Pattern for access)
- LiveData data holder for passing crime data between database and fragments/activity
- DialogFragment for picking date of each crime
- Material3 design

## Future features

- Implicit intents for using contacts app to choose a suspect and for taking a picture of the crime
- Login page and display office crimes dependent on which office a user works in

## Video Demo

<img src='https://github.com/respeese/CriminalIntent/blob/master/CriminalIntentDemo.gif' title='Video Demo' width='240' alt='Video Demo' />

## Notes

I used this project to learn about fragment navigation and passing data between fragments. I also learned about using the Room library to manage a database.

## License

Copyright **2023** **Ryan Speese**

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0
