Logger.java
Contains the Singleton implementation.

Uses a private constructor.

Provides the getInstance() method to return the single object.

Includes a log() method to print log messages.

SingletonTest.java
Creates two references using Logger.getInstance().

Logs messages using both references.

Verifies that both references point to the same object.
