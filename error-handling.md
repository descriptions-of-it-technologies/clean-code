# Error Handling.





## Contents at a Glance.
* [About](#about)
* [Documentation.](#documentation)
* [Help](#help)





## About.





## Documentation.





##
* Use exceptions, not return codes.
* try-catch-finally block.
* Not catch Errors.
* Not catch Throwable.
* Catch all exceptions.
* Never use checked exceptions.
* Context in exceptions
* Context in exceptions message.
* Custom exception always should have a constructor that takes another exception. 
  Example -> UILayoutException(DomainLayoutException(DaoLayoutException(RecordNotFound())))
* Don't return null. Think about 'null object pattern'.
* Don't pass null to methods





## Help.