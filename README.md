<p align="center">
  <h3 align="center">Simple Microservices</h3>

  <p align="center">
    Simple set of microservices
</p>

## About

My goal for this project was to learn how microservices work and how are they built using .NET Core. 

### Technologies Used

* []() .NET Core 5.0
* []() Ocelot (Api Gateway)
* []() Json Web Token (JWT)


<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

* []() .NET Core 5

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/mikkoryynanen/Simple-Web-Api.git
   ```
2. Init and update submodules
   ```sh
    git submodule init
    git submodule update
   ```


<!-- USAGE EXAMPLES -->
## Usage

First you must authenticate the user by asking for an authentication token. This can be done by using the following request
```sh
    /user/authenticate
```
Once you have gotten the authentication token, send it as an Authorization header along with the following request
```sh
    /weatherforecast?cityname={cityName}
```

## Acknowledgements

Note that this project is made for demonstration purposes only.

