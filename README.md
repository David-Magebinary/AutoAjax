## Introduction
### Background

We need an Ajax framework to helps us quickly implement an universal solution to all our projects. Most of our projects are ecommerce website which would need quite a lot Ajax effect to improve the user experience.


### Key requirements
The following core requirements:

1. Allows to define a messaging or an alert system. (eg. sweetalert)

2. Allows to simple initialize API point to run with all default settings.

3. Various API options && all API point should be avaiable in by using data-attributes in HTML.


### API options

#### message
Type: ``` Object ``` \
Default: ``` swal ```

The name of the messaging system which allows to display loading or response message

#### request
Type: ``` String ``` \
Default: ``` empty ```


A string containing the URL to which the request is sent.

#### requestMethod
Type: ``` String ```\
Default: ``` GET ```

The HTTP method to use for the request (e.g. ``` POST ```, ``` GET ```)

#### requestUpdate
Type: ``` String ``` or ``` Function() ```\
Default: ``` empty ```

The update method or element would be executed or modified after the response has been post back.

#### requestLoading
Type: ``` String ``` or ``` Function() ```\
Default: ``` Function() ```

The loading object or string which would be executed or rendered.

#### onSuccess
Type: ``` Function() ``` \
Default: ``` empty ```

The callback would be executed after the response has been post back and considered as a success request.


#### onFail
Type: ``` Function() ``` \
Default: ``` empty ```

The callback would be executed after the response has been post back and considered as a failed request.

#### beforeSend
Type: ``` Function() ``` \
Default: ``` empty ```

The callback would be executed before the request has been sent to the request URL.
