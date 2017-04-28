# Exit Popup Code Snippet

The exit popup code snippet can be found under the screen popup section within the developer section.

There are three ways in which you can use the code snippet within your HTML page.

## Pass all the customer details within the URL


The first way is to include the customer_id and phone variables within the scripts URL:


> Example URL

```shell
https://iqxstatic.s3.amazonaws.com/modal/snippet.js?iqxUrl=https://public-api.iqxamplify.com/V1/&iqxIntegrationId=18355178&customerId=4561572551&phone=404-333-7777

```

## Call the init function with a callback


The second way is to call the amplifyModal.onInit function and set the customerId and phone number in the callback as follows:

> Example Function

```shell
amplifyModal.onInit(function(){
  amplifyModal.customerId = "1234565";
  amplifyModal.phone = "778 995 2877";
});

```

## Describe the object the holds the customer information

The last way is to set the path to a global object that contains the customerId an dphone number of the customer. This is useful if you can only set the javascript URL, but not call a funciton on the page. An example is as follows:

> Example URL

```shell
https://iqxstatic.s3.amazonaws.com/modal/snippet.js?iqxUrl=https://public-api.iqxamplify.com/V1/&iqxIntegrationId=18355178&customerId=4561572551&phone=404-333-7777&customerIdVariableName=GlobalObject.customer_id&phoneVariableName=GlobalObject.checkout.phone

```