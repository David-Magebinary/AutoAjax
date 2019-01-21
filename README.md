## Introduction
### Background

We need an Ajax framework to helps us quickly implement an universal solution to all our projects. Most of our projects are ecommerce website which would need quite a lot Ajax effect to improve the user experience.


### Key requirements
The following core requirements:

1. Allows to define a messaging or an alert system. (eg. sweetalert)
2. Allows to simple initialize API point to run with all default settings.
3. Various API options && all API point should be avaiable in by using data-attributes in HTML.

### How to use

Add ```data-request``` attribute to any ```<a>, <buitton>, <button type="submit">```, or add ```data-request-form``` to any ``` <button type="submit"> ```

### API options

#### request
Type: ``` String ``` \
Default: ``` empty ``` \
Data attribute: ``` data-request ``` \
Required: true | false

A string containing the URL to which the request is sent. The value would not be required when user defined a requestForm element.

#### form
Type: ``` String ``` \
Default: ``` empty ``` \
Data attribute: ``` data-request-form ``` \
Required: false | true

The id of the form element which would be submitted by Ajax. The attribute would be required value when the user wants AutoAjax to be worked on a button with ``` type="submit" ```.

#### method
Type: ``` String ``` \
Default: ``` GET ``` \
Data attribute: ``` data-request-method ```

The HTTP method to use for the request (e.g. ``` POST ```, ``` GET ```)

#### loading
Type: ``` String ``` \
Default: ``` empty ``` \
Data attribute: ``` data-request-loading ```

The element's selector which would be modified while the request is sending through.

#### loadingAnimation
Type: ``` String ``` or ``` Function() ```\
Default: ``` bootstrap ``` \
Data attribute: ``` data-request-loading-animation ``` \
Values: ``` bootstrap, swal ```

The animation name for loading effect.

#### onSuccess
Type: ``` Function() ``` \
Default: ``` empty ```

The callback would be executed after the response has been post back and considered as a success request.

#### message
Type: ``` Object ``` \
Default: ``` swal ```

The name of the messaging system which allows to display loading or response message

#### onFail
Type: ``` Function() ``` \
Default: ``` empty ```

The callback would be executed after the response has been post back and considered as a failed request.

#### beforeSend
Type: ``` Function() ``` \
Default: ``` empty ```

The callback would be executed before the request has been sent to the request URL.
