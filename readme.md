# ASP.NET SignalR library for Java and Android
For more infomation on SignalR, please look at the official SignalR website (http://signalr.net/).

This library can be used in both Java and Android applications.

## Is this the official SignalR library?
This repository was forked from the official [SignalR repository](https://github.com/SignalR/java-client) on June 2015. Since that date, changes have been made to the code to fix issues that existed on the official code. However, these changes have never been merged back to the official repository.

## Documentation
Official SignalR [documentation](http://asp.net/signalr)

## LICENSE
The original [Apache 2.0 License](https://github.com/SignalR/SignalR/blob/master/LICENSE.md)

## Contributing

See the original [contribution  guidelines](https://github.com/SignalR/SignalR/blob/master/CONTRIBUTING.md)

## Building the source

```
git clone git@github.com:arminelec/signalr-java-client.git (or https if you use https)
```

Open Android Studio, click "Import Non-Android Studio Project" and select the cloned directory 

Build the project.

The signalr-client-sdk.jar will be generated inside the /signalr-client-sdk/build/libs folder

The signalr-client-sdk-android.aar will be generated inside the /signalr-client-sdk-android/build/outputs/aar folder

## Running the tests:
	
Run the signalr-client-tests project as a JUnit test.

## Using the library in a Java application:

Add the signalr-client-sdk.jar and gson library gradle dependencyto the project.

## Using the library in an Android application:

Add the signalr-client-sdk.jar, signalr-client-sdk-android.jar gson library as a gradle dependency to the project.

In the code, before using the library, initialize the platform to use android-specific libraries and compatibility with older Android versions:
	- Platform.loadPlatformComponent(new AndroidPlatformComponent());


## Questions?
The SignalR team hangs out in the [signalr](http://jabbr.net/#/rooms/signalr) room at on [JabbR](http://jabbr.net/).
