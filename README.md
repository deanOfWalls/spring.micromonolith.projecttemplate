# Spring Vanilla JS Full Stack Project template 

### Purpose
* To provide a biolerplate full-stack monolithic application which is used as a template for extension

### How to Use From CLI
1. Execute the command below from the root directory of this project to serve the application.
     * `./build.sh 8080`
2. Navigate to `localhost/8080` from a browser (`Chrome`, or `Firefox`)


### How to Use From IDE
  1. Run this application by running the main method in `DemoApplication`.
  2. Navigate to the server port specified in the [application.properties file](./src/main/resources/application.properties). By default, the port number is `8080`
  3. Navigate to `localhost/8080` from a browser (`Chrome`, or `Firefox`)

### How to rebrand application
  1. Execute the command below replacing `$your-brand-name` with a new literal value
     * `rebrand.sh $your-brand-name` (for example `rebrand.sh johndoe`)
     * this will change all instances of `curriculeon` to the respective `$your-brand-name` value. 