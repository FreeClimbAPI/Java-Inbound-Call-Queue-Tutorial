# Java - Inbound Call Queue Tutorial

This project serves as a guide to help you build an application with FreeClimb. View this tutorial on [FreeClimb.com](https://docs.freeclimb.com/docs/inbound-call-queue#section-java). Specifically, the project will:

- Add a Caller to a queue
- Get digits from the caller
- Exit the queue when a key is pressed

## Setting up your new app within your FreeClimb account

To get started using a FreeClimb account, follow the instructions [here](https://docs.freeclimb.com/docs/getting-started-with-freeclimb).

## Setting up the Inbound Call Queue Tutorial

1. Configure environment variables.

| ENV VARIABLE | DESCRIPTION                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------- |
| ACCOUNT_ID   | Account ID which can be found under [API Keys](https://www.freeclimb.com/dashboard/portal/account/authentication) in Dashboard           |
| AUTH_TOKEN   | Authentication Token which can be found under [API Keys](https://www.freeclimb.com/dashboard/portal/account/authentication) in Dashboard |
|  HOST        |  The host url where your application is hosted (e.g. yourHostedApp.com)                                                                  |

## Building and Runnning the Tutorial

1. Build and run the application using command:

   ```bash
   $ gradle build && java -Dserver.port=3000 -jar build/libs/gs-spring-boot-0.1.0.jar
   ```

## Getting Help

If you are experiencing difficulties, [contact support](https://freeclimb.com/support).
