## download node modules
Join your project folder in the terminal and run the following command to download node modules

```sh
npm install
```

## Update pods
Join the ios project folder in the terminal and run the following command to update pod modules

```sh
pod update
pod install
```

## Update pods
Join the ios project folder in the terminal and run the following command to update pod modules

```sh
pod update
pod install
```

## Unit Test
Go back to the project folder in the terminal and run the following command to start unit test

```sh
npm test
```

## Build your app and run Detox tests

#### 1. Build your app

Use the Detox command line tools to build your project on ios simulator:

```sh
detox build --configuration ios.sim.debug
```

> TIP: Notice that the actual build command was specified in the Detox configuration above

#### 2. Run the tests (finally)

Use the Detox command line tools to test your project on ios simulator:

```sh
detox test --configuration ios.sim.debug
```

That's it. Your first failing Detox test is running!
