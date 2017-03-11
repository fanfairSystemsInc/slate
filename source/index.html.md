---
title: iQX Amplify API Reference v1.0.0
language_tabs:
  - shell: Shell
  - http: HTTP
  - html: JavaScript
  - javascript: Node.JS
  - python: Python
  - ruby: Ruby
  - java: Java
toc_footers: []
includes:
   - errors
   - webhooks
search: true
highlight_theme: darkula
---

# iQX Amplify API Reference v1.0.0

Welcome to the iQX Amplify API reference. This is a live example of how you can use [iQX Amplify](http://app.iqxamplify.com/) to integrate your own e-commerce store or ticketing engine.

The iQX Amplify API is organized around the [REST](http://en.wikipedia.org/wiki/Representational_State_Transfer) mothodology, and it uses resource-oriented URLs, and common HTTP response codes to indicate API errors. All requests are authenticated using an `api-key` which can be obtained from your developer dashboard within iQX Amplify.

Base URL = http://public-api.iqxamplify.com/V1

<a href="https://documents.iqxamplify.com/termsofservice">Terms of service</a>
Email: <a href="mailto:development@iqxcorp.com">Support</a>


# Authentication



* API Key
- Parameter Name: **api_key**, in: header.





# Default

## X-SWAGGER-ROUTER-CONTROLLER /stores/

> Code samples

````shell
# You can also use wget
curl -X x-swagger-router-controller http://localhost:10010/V1/stores/
````

````http
X-SWAGGER-ROUTER-CONTROLLER http://localhost:10010/V1/stores/ HTTP/1.1
Host: localhost:10010
Content-Type: application/json
Accept: application/json
````

````html
<script>
  $.ajax({
    url: 'http://localhost:10010/V1/stores/',
    method: 'x-swagger-router-controller',
    success: function(data) {
      console.log(JSON.stringify(data));
    }
  })
</script>
````

````javascript
const request = require('node-fetch');
fetch('http://localhost:10010/V1/stores/', { method: 'X-SWAGGER-ROUTER-CONTROLLER'})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});
````

````ruby
require 'rest-client'
require 'json'

result = RestClient.x-swagger-router-controller 'http://localhost:10010/V1/stores/', params:
  {
    # TODO
  }

p JSON.parse(result)
````

````python
import requests

r = requests.x-swagger-router-controller('http://localhost:10010/V1/stores/', params={
  # TODO
})

print r.json()
````

````java
URL obj = new URL("http://localhost:10010/V1/stores/");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("X-SWAGGER-ROUTER-CONTROLLER");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());
````

### Responses

Status|Meaning|Description
---|---|---|

<aside class="success">
This operation does not require authentication
</aside>

## X-SWAGGER-ROUTER-CONTROLLER /stores/{id}

> Code samples

````shell
# You can also use wget
curl -X x-swagger-router-controller http://localhost:10010/V1/stores/{id}
````

````http
X-SWAGGER-ROUTER-CONTROLLER http://localhost:10010/V1/stores/{id} HTTP/1.1
Host: localhost:10010
Content-Type: application/json
Accept: application/json
````

````html
<script>
  $.ajax({
    url: 'http://localhost:10010/V1/stores/{id}',
    method: 'x-swagger-router-controller',
    success: function(data) {
      console.log(JSON.stringify(data));
    }
  })
</script>
````

````javascript
const request = require('node-fetch');
fetch('http://localhost:10010/V1/stores/{id}', { method: 'X-SWAGGER-ROUTER-CONTROLLER'})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});
````

````ruby
require 'rest-client'
require 'json'

result = RestClient.x-swagger-router-controller 'http://localhost:10010/V1/stores/{id}', params:
  {
    # TODO
  }

p JSON.parse(result)
````

````python
import requests

r = requests.x-swagger-router-controller('http://localhost:10010/V1/stores/{id}', params={
  # TODO
})

print r.json()
````

````java
URL obj = new URL("http://localhost:10010/V1/stores/{id}");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("X-SWAGGER-ROUTER-CONTROLLER");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());
````

### Responses

Status|Meaning|Description
---|---|---|

<aside class="success">
This operation does not require authentication
</aside>

## X-SWAGGER-ROUTER-CONTROLLER /customers/

> Code samples

````shell
# You can also use wget
curl -X x-swagger-router-controller http://localhost:10010/V1/customers/
````

````http
X-SWAGGER-ROUTER-CONTROLLER http://localhost:10010/V1/customers/ HTTP/1.1
Host: localhost:10010
Content-Type: application/json
Accept: application/json
````

````html
<script>
  $.ajax({
    url: 'http://localhost:10010/V1/customers/',
    method: 'x-swagger-router-controller',
    success: function(data) {
      console.log(JSON.stringify(data));
    }
  })
</script>
````

````javascript
const request = require('node-fetch');
fetch('http://localhost:10010/V1/customers/', { method: 'X-SWAGGER-ROUTER-CONTROLLER'})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});
````

````ruby
require 'rest-client'
require 'json'

result = RestClient.x-swagger-router-controller 'http://localhost:10010/V1/customers/', params:
  {
    # TODO
  }

p JSON.parse(result)
````

````python
import requests

r = requests.x-swagger-router-controller('http://localhost:10010/V1/customers/', params={
  # TODO
})

print r.json()
````

````java
URL obj = new URL("http://localhost:10010/V1/customers/");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("X-SWAGGER-ROUTER-CONTROLLER");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());
````

### Responses

Status|Meaning|Description
---|---|---|

<aside class="success">
This operation does not require authentication
</aside>

## X-SWAGGER-ROUTER-CONTROLLER /customers/{id}

> Code samples

````shell
# You can also use wget
curl -X x-swagger-router-controller http://localhost:10010/V1/customers/{id}
````

````http
X-SWAGGER-ROUTER-CONTROLLER http://localhost:10010/V1/customers/{id} HTTP/1.1
Host: localhost:10010
Content-Type: application/json
Accept: application/json
````

````html
<script>
  $.ajax({
    url: 'http://localhost:10010/V1/customers/{id}',
    method: 'x-swagger-router-controller',
    success: function(data) {
      console.log(JSON.stringify(data));
    }
  })
</script>
````

````javascript
const request = require('node-fetch');
fetch('http://localhost:10010/V1/customers/{id}', { method: 'X-SWAGGER-ROUTER-CONTROLLER'})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});
````

````ruby
require 'rest-client'
require 'json'

result = RestClient.x-swagger-router-controller 'http://localhost:10010/V1/customers/{id}', params:
  {
    # TODO
  }

p JSON.parse(result)
````

````python
import requests

r = requests.x-swagger-router-controller('http://localhost:10010/V1/customers/{id}', params={
  # TODO
})

print r.json()
````

````java
URL obj = new URL("http://localhost:10010/V1/customers/{id}");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("X-SWAGGER-ROUTER-CONTROLLER");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());
````

### Responses

Status|Meaning|Description
---|---|---|

<aside class="success">
This operation does not require authentication
</aside>

## X-SWAGGER-ROUTER-CONTROLLER /products/

> Code samples

````shell
# You can also use wget
curl -X x-swagger-router-controller http://localhost:10010/V1/products/
````

````http
X-SWAGGER-ROUTER-CONTROLLER http://localhost:10010/V1/products/ HTTP/1.1
Host: localhost:10010
Content-Type: application/json
Accept: application/json
````

````html
<script>
  $.ajax({
    url: 'http://localhost:10010/V1/products/',
    method: 'x-swagger-router-controller',
    success: function(data) {
      console.log(JSON.stringify(data));
    }
  })
</script>
````

````javascript
const request = require('node-fetch');
fetch('http://localhost:10010/V1/products/', { method: 'X-SWAGGER-ROUTER-CONTROLLER'})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});
````

````ruby
require 'rest-client'
require 'json'

result = RestClient.x-swagger-router-controller 'http://localhost:10010/V1/products/', params:
  {
    # TODO
  }

p JSON.parse(result)
````

````python
import requests

r = requests.x-swagger-router-controller('http://localhost:10010/V1/products/', params={
  # TODO
})

print r.json()
````

````java
URL obj = new URL("http://localhost:10010/V1/products/");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("X-SWAGGER-ROUTER-CONTROLLER");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());
````

### Responses

Status|Meaning|Description
---|---|---|

<aside class="success">
This operation does not require authentication
</aside>

## X-SWAGGER-ROUTER-CONTROLLER /products/{id}

> Code samples

````shell
# You can also use wget
curl -X x-swagger-router-controller http://localhost:10010/V1/products/{id}
````

````http
X-SWAGGER-ROUTER-CONTROLLER http://localhost:10010/V1/products/{id} HTTP/1.1
Host: localhost:10010
Content-Type: application/json
Accept: application/json
````

````html
<script>
  $.ajax({
    url: 'http://localhost:10010/V1/products/{id}',
    method: 'x-swagger-router-controller',
    success: function(data) {
      console.log(JSON.stringify(data));
    }
  })
</script>
````

````javascript
const request = require('node-fetch');
fetch('http://localhost:10010/V1/products/{id}', { method: 'X-SWAGGER-ROUTER-CONTROLLER'})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});
````

````ruby
require 'rest-client'
require 'json'

result = RestClient.x-swagger-router-controller 'http://localhost:10010/V1/products/{id}', params:
  {
    # TODO
  }

p JSON.parse(result)
````

````python
import requests

r = requests.x-swagger-router-controller('http://localhost:10010/V1/products/{id}', params={
  # TODO
})

print r.json()
````

````java
URL obj = new URL("http://localhost:10010/V1/products/{id}");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("X-SWAGGER-ROUTER-CONTROLLER");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());
````

### Responses

Status|Meaning|Description
---|---|---|

<aside class="success">
This operation does not require authentication
</aside>

## X-SWAGGER-ROUTER-CONTROLLER /orders/

> Code samples

````shell
# You can also use wget
curl -X x-swagger-router-controller http://localhost:10010/V1/orders/
````

````http
X-SWAGGER-ROUTER-CONTROLLER http://localhost:10010/V1/orders/ HTTP/1.1
Host: localhost:10010
Content-Type: application/json
Accept: application/json
````

````html
<script>
  $.ajax({
    url: 'http://localhost:10010/V1/orders/',
    method: 'x-swagger-router-controller',
    success: function(data) {
      console.log(JSON.stringify(data));
    }
  })
</script>
````

````javascript
const request = require('node-fetch');
fetch('http://localhost:10010/V1/orders/', { method: 'X-SWAGGER-ROUTER-CONTROLLER'})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});
````

````ruby
require 'rest-client'
require 'json'

result = RestClient.x-swagger-router-controller 'http://localhost:10010/V1/orders/', params:
  {
    # TODO
  }

p JSON.parse(result)
````

````python
import requests

r = requests.x-swagger-router-controller('http://localhost:10010/V1/orders/', params={
  # TODO
})

print r.json()
````

````java
URL obj = new URL("http://localhost:10010/V1/orders/");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("X-SWAGGER-ROUTER-CONTROLLER");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());
````

### Responses

Status|Meaning|Description
---|---|---|

<aside class="success">
This operation does not require authentication
</aside>

## X-SWAGGER-ROUTER-CONTROLLER /orders/{id}

> Code samples

````shell
# You can also use wget
curl -X x-swagger-router-controller http://localhost:10010/V1/orders/{id}
````

````http
X-SWAGGER-ROUTER-CONTROLLER http://localhost:10010/V1/orders/{id} HTTP/1.1
Host: localhost:10010
Content-Type: application/json
Accept: application/json
````

````html
<script>
  $.ajax({
    url: 'http://localhost:10010/V1/orders/{id}',
    method: 'x-swagger-router-controller',
    success: function(data) {
      console.log(JSON.stringify(data));
    }
  })
</script>
````

````javascript
const request = require('node-fetch');
fetch('http://localhost:10010/V1/orders/{id}', { method: 'X-SWAGGER-ROUTER-CONTROLLER'})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});
````

````ruby
require 'rest-client'
require 'json'

result = RestClient.x-swagger-router-controller 'http://localhost:10010/V1/orders/{id}', params:
  {
    # TODO
  }

p JSON.parse(result)
````

````python
import requests

r = requests.x-swagger-router-controller('http://localhost:10010/V1/orders/{id}', params={
  # TODO
})

print r.json()
````

````java
URL obj = new URL("http://localhost:10010/V1/orders/{id}");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("X-SWAGGER-ROUTER-CONTROLLER");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());
````

### Responses

Status|Meaning|Description
---|---|---|

<aside class="success">
This operation does not require authentication
</aside>

## X-SWAGGER-ROUTER-CONTROLLER /events/

> Code samples

````shell
# You can also use wget
curl -X x-swagger-router-controller http://localhost:10010/V1/events/
````

````http
X-SWAGGER-ROUTER-CONTROLLER http://localhost:10010/V1/events/ HTTP/1.1
Host: localhost:10010
Content-Type: application/json
Accept: application/json
````

````html
<script>
  $.ajax({
    url: 'http://localhost:10010/V1/events/',
    method: 'x-swagger-router-controller',
    success: function(data) {
      console.log(JSON.stringify(data));
    }
  })
</script>
````

````javascript
const request = require('node-fetch');
fetch('http://localhost:10010/V1/events/', { method: 'X-SWAGGER-ROUTER-CONTROLLER'})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});
````

````ruby
require 'rest-client'
require 'json'

result = RestClient.x-swagger-router-controller 'http://localhost:10010/V1/events/', params:
  {
    # TODO
  }

p JSON.parse(result)
````

````python
import requests

r = requests.x-swagger-router-controller('http://localhost:10010/V1/events/', params={
  # TODO
})

print r.json()
````

````java
URL obj = new URL("http://localhost:10010/V1/events/");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("X-SWAGGER-ROUTER-CONTROLLER");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());
````

### Responses

Status|Meaning|Description
---|---|---|

<aside class="success">
This operation does not require authentication
</aside>

## X-SWAGGER-ROUTER-CONTROLLER /events/{id}

> Code samples

````shell
# You can also use wget
curl -X x-swagger-router-controller http://localhost:10010/V1/events/{id}
````

````http
X-SWAGGER-ROUTER-CONTROLLER http://localhost:10010/V1/events/{id} HTTP/1.1
Host: localhost:10010
Content-Type: application/json
Accept: application/json
````

````html
<script>
  $.ajax({
    url: 'http://localhost:10010/V1/events/{id}',
    method: 'x-swagger-router-controller',
    success: function(data) {
      console.log(JSON.stringify(data));
    }
  })
</script>
````

````javascript
const request = require('node-fetch');
fetch('http://localhost:10010/V1/events/{id}', { method: 'X-SWAGGER-ROUTER-CONTROLLER'})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});
````

````ruby
require 'rest-client'
require 'json'

result = RestClient.x-swagger-router-controller 'http://localhost:10010/V1/events/{id}', params:
  {
    # TODO
  }

p JSON.parse(result)
````

````python
import requests

r = requests.x-swagger-router-controller('http://localhost:10010/V1/events/{id}', params={
  # TODO
})

print r.json()
````

````java
URL obj = new URL("http://localhost:10010/V1/events/{id}");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("X-SWAGGER-ROUTER-CONTROLLER");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());
````

### Responses

Status|Meaning|Description
---|---|---|

<aside class="success">
This operation does not require authentication
</aside>

## X-SWAGGER-ROUTER-CONTROLLER /events/{id}/tickets/

> Code samples

````shell
# You can also use wget
curl -X x-swagger-router-controller http://localhost:10010/V1/events/{id}/tickets/
````

````http
X-SWAGGER-ROUTER-CONTROLLER http://localhost:10010/V1/events/{id}/tickets/ HTTP/1.1
Host: localhost:10010
Content-Type: application/json
Accept: application/json
````

````html
<script>
  $.ajax({
    url: 'http://localhost:10010/V1/events/{id}/tickets/',
    method: 'x-swagger-router-controller',
    success: function(data) {
      console.log(JSON.stringify(data));
    }
  })
</script>
````

````javascript
const request = require('node-fetch');
fetch('http://localhost:10010/V1/events/{id}/tickets/', { method: 'X-SWAGGER-ROUTER-CONTROLLER'})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});
````

````ruby
require 'rest-client'
require 'json'

result = RestClient.x-swagger-router-controller 'http://localhost:10010/V1/events/{id}/tickets/', params:
  {
    # TODO
  }

p JSON.parse(result)
````

````python
import requests

r = requests.x-swagger-router-controller('http://localhost:10010/V1/events/{id}/tickets/', params={
  # TODO
})

print r.json()
````

````java
URL obj = new URL("http://localhost:10010/V1/events/{id}/tickets/");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("X-SWAGGER-ROUTER-CONTROLLER");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());
````

### Responses

Status|Meaning|Description
---|---|---|

<aside class="success">
This operation does not require authentication
</aside>

## X-SWAGGER-ROUTER-CONTROLLER /events/{id}/tickets/{tickets_id}/

> Code samples

````shell
# You can also use wget
curl -X x-swagger-router-controller http://localhost:10010/V1/events/{id}/tickets/{tickets_id}/
````

````http
X-SWAGGER-ROUTER-CONTROLLER http://localhost:10010/V1/events/{id}/tickets/{tickets_id}/ HTTP/1.1
Host: localhost:10010
Content-Type: application/json
Accept: application/json
````

````html
<script>
  $.ajax({
    url: 'http://localhost:10010/V1/events/{id}/tickets/{tickets_id}/',
    method: 'x-swagger-router-controller',
    success: function(data) {
      console.log(JSON.stringify(data));
    }
  })
</script>
````

````javascript
const request = require('node-fetch');
fetch('http://localhost:10010/V1/events/{id}/tickets/{tickets_id}/', { method: 'X-SWAGGER-ROUTER-CONTROLLER'})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});
````

````ruby
require 'rest-client'
require 'json'

result = RestClient.x-swagger-router-controller 'http://localhost:10010/V1/events/{id}/tickets/{tickets_id}/', params:
  {
    # TODO
  }

p JSON.parse(result)
````

````python
import requests

r = requests.x-swagger-router-controller('http://localhost:10010/V1/events/{id}/tickets/{tickets_id}/', params={
  # TODO
})

print r.json()
````

````java
URL obj = new URL("http://localhost:10010/V1/events/{id}/tickets/{tickets_id}/");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("X-SWAGGER-ROUTER-CONTROLLER");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());
````

### Responses

Status|Meaning|Description
---|---|---|

<aside class="success">
This operation does not require authentication
</aside>

## X-SWAGGER-ROUTER-CONTROLLER /tickets/

> Code samples

````shell
# You can also use wget
curl -X x-swagger-router-controller http://localhost:10010/V1/tickets/
````

````http
X-SWAGGER-ROUTER-CONTROLLER http://localhost:10010/V1/tickets/ HTTP/1.1
Host: localhost:10010
Content-Type: application/json
Accept: application/json
````

````html
<script>
  $.ajax({
    url: 'http://localhost:10010/V1/tickets/',
    method: 'x-swagger-router-controller',
    success: function(data) {
      console.log(JSON.stringify(data));
    }
  })
</script>
````

````javascript
const request = require('node-fetch');
fetch('http://localhost:10010/V1/tickets/', { method: 'X-SWAGGER-ROUTER-CONTROLLER'})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});
````

````ruby
require 'rest-client'
require 'json'

result = RestClient.x-swagger-router-controller 'http://localhost:10010/V1/tickets/', params:
  {
    # TODO
  }

p JSON.parse(result)
````

````python
import requests

r = requests.x-swagger-router-controller('http://localhost:10010/V1/tickets/', params={
  # TODO
})

print r.json()
````

````java
URL obj = new URL("http://localhost:10010/V1/tickets/");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("X-SWAGGER-ROUTER-CONTROLLER");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());
````

### Responses

Status|Meaning|Description
---|---|---|

<aside class="success">
This operation does not require authentication
</aside>

## X-SWAGGER-ROUTER-CONTROLLER /tickets/{id}

> Code samples

````shell
# You can also use wget
curl -X x-swagger-router-controller http://localhost:10010/V1/tickets/{id}
````

````http
X-SWAGGER-ROUTER-CONTROLLER http://localhost:10010/V1/tickets/{id} HTTP/1.1
Host: localhost:10010
Content-Type: application/json
Accept: application/json
````

````html
<script>
  $.ajax({
    url: 'http://localhost:10010/V1/tickets/{id}',
    method: 'x-swagger-router-controller',
    success: function(data) {
      console.log(JSON.stringify(data));
    }
  })
</script>
````

````javascript
const request = require('node-fetch');
fetch('http://localhost:10010/V1/tickets/{id}', { method: 'X-SWAGGER-ROUTER-CONTROLLER'})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});
````

````ruby
require 'rest-client'
require 'json'

result = RestClient.x-swagger-router-controller 'http://localhost:10010/V1/tickets/{id}', params:
  {
    # TODO
  }

p JSON.parse(result)
````

````python
import requests

r = requests.x-swagger-router-controller('http://localhost:10010/V1/tickets/{id}', params={
  # TODO
})

print r.json()
````

````java
URL obj = new URL("http://localhost:10010/V1/tickets/{id}");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("X-SWAGGER-ROUTER-CONTROLLER");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());
````

### Responses

Status|Meaning|Description
---|---|---|

<aside class="success">
This operation does not require authentication
</aside>

## X-SWAGGER-PIPE /swagger

> Code samples

````shell
# You can also use wget
curl -X x-swagger-pipe http://localhost:10010/V1/swagger
````

````http
X-SWAGGER-PIPE http://localhost:10010/V1/swagger HTTP/1.1
Host: localhost:10010
Content-Type: application/json
Accept: application/json
````

````html
<script>
  $.ajax({
    url: 'http://localhost:10010/V1/swagger',
    method: 'x-swagger-pipe',
    success: function(data) {
      console.log(JSON.stringify(data));
    }
  })
</script>
````

````javascript
const request = require('node-fetch');
fetch('http://localhost:10010/V1/swagger', { method: 'X-SWAGGER-PIPE'})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});
````

````ruby
require 'rest-client'
require 'json'

result = RestClient.x-swagger-pipe 'http://localhost:10010/V1/swagger', params:
  {
    # TODO
  }

p JSON.parse(result)
````

````python
import requests

r = requests.x-swagger-pipe('http://localhost:10010/V1/swagger', params={
  # TODO
})

print r.json()
````

````java
URL obj = new URL("http://localhost:10010/V1/swagger");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("X-SWAGGER-PIPE");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());
````

### Responses

Status|Meaning|Description
---|---|---|

<aside class="success">
This operation does not require authentication
</aside>

# Stores

Store methods provide access to information and operations relating to the store.

## FindStores

> Code samples

````shell
# You can also use wget
curl -X get http://localhost:10010/V1/stores/
````

````http
GET http://localhost:10010/V1/stores/ HTTP/1.1
Host: localhost:10010
Content-Type: application/json
Accept: application/json
````

````html
<script>
  $.ajax({
    url: 'http://localhost:10010/V1/stores/',
    method: 'get',
    success: function(data) {
      console.log(JSON.stringify(data));
    }
  })
</script>
````

````javascript
const request = require('node-fetch');
fetch('http://localhost:10010/V1/stores/', { method: 'GET'})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});
````

````ruby
require 'rest-client'
require 'json'

result = RestClient.get 'http://localhost:10010/V1/stores/', params:
  {
    # TODO
  }

p JSON.parse(result)
````

````python
import requests

r = requests.get('http://localhost:10010/V1/stores/', params={
  # TODO
})

print r.json()
````

````java
URL obj = new URL("http://localhost:10010/V1/stores/");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());
````

`GET /stores/`

*Retrieve all stores*

Retrieve all stores

### Responses

Status|Meaning|Description
---|---|---|
200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|Store response
default|Default|Error

> Example responses

````json
[
  {
    "_key": "string",
    "type": "string",
    "url": "string",
    "business_name": "string",
    "site_url": "string",
    "terms_of_service": "string",
    "modified_date": "2017-02-12T00:24:35Z",
    "has_integration": true,
    "whitelist_email_on_purchase": true,
    "whitelist_popup_on_purchase": true
  }
]
````
````json
{}
````
<aside class="warning">
To perform this operation, you must be authenticated by means of one of the following methods:
apiKey
</aside>


## CreateOrUpdateStore

> Code samples

````shell
# You can also use wget
curl -X post http://localhost:10010/V1/stores/
````

````http
POST http://localhost:10010/V1/stores/ HTTP/1.1
Host: localhost:10010
Content-Type: application/json
Accept: application/json
````

````html
<script>
  $.ajax({
    url: 'http://localhost:10010/V1/stores/',
    method: 'post',
    success: function(data) {
      console.log(JSON.stringify(data));
    }
  })
</script>
````

````javascript
const request = require('node-fetch');
fetch('http://localhost:10010/V1/stores/', { method: 'POST'})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});
````

````ruby
require 'rest-client'
require 'json'

result = RestClient.post 'http://localhost:10010/V1/stores/', params:
  {
    # TODO
  }

p JSON.parse(result)
````

````python
import requests

r = requests.post('http://localhost:10010/V1/stores/', params={
  # TODO
})

print r.json()
````

````java
URL obj = new URL("http://localhost:10010/V1/stores/");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("POST");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());
````

`POST /stores/`

*Create or update a store*

Create or update a store

### Parameters

Parameter|In|Type|Required|Description
---|---|---|---|---|
store|body|Store|true|Add or update store details



> Body parameter

````json
{
  "_key": "string",
  "type": "string",
  "url": "string",
  "business_name": "string",
  "site_url": "string",
  "terms_of_service": "string",
  "modified_date": "2017-02-12T00:24:35Z",
  "has_integration": true,
  "whitelist_email_on_purchase": true,
  "whitelist_popup_on_purchase": true
}
````
### Responses

Status|Meaning|Description
---|---|---|
200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|Store object response
default|Default|Error

> Example responses

````json
[
  {
    "_key": "string",
    "type": "string",
    "url": "string",
    "business_name": "string",
    "site_url": "string",
    "terms_of_service": "string",
    "modified_date": "2017-02-12T00:24:35Z",
    "has_integration": true,
    "whitelist_email_on_purchase": true,
    "whitelist_popup_on_purchase": true
  }
]
````
````json
{}
````
<aside class="warning">
To perform this operation, you must be authenticated by means of one of the following methods:
apiKey
</aside>


## FindStoresById

> Code samples

````shell
# You can also use wget
curl -X get http://localhost:10010/V1/stores/{id}
````

````http
GET http://localhost:10010/V1/stores/{id} HTTP/1.1
Host: localhost:10010
Content-Type: application/json
Accept: application/json
````

````html
<script>
  $.ajax({
    url: 'http://localhost:10010/V1/stores/{id}',
    method: 'get',
    success: function(data) {
      console.log(JSON.stringify(data));
    }
  })
</script>
````

````javascript
const request = require('node-fetch');
fetch('http://localhost:10010/V1/stores/{id}', { method: 'GET'})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});
````

````ruby
require 'rest-client'
require 'json'

result = RestClient.get 'http://localhost:10010/V1/stores/{id}', params:
  {
    # TODO
  }

p JSON.parse(result)
````

````python
import requests

r = requests.get('http://localhost:10010/V1/stores/{id}', params={
  # TODO
})

print r.json()
````

````java
URL obj = new URL("http://localhost:10010/V1/stores/{id}");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());
````

`GET /stores/{id}`

*Retrieve a single store by id*

Retrieve a single store by id

### Parameters

Parameter|In|Type|Required|Description
---|---|---|---|---|
id|path|string|true|ID of the store to get



### Responses

Status|Meaning|Description
---|---|---|
200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|Store object response
default|Default|Error

> Example responses

````json
{
  "_key": "string",
  "type": "string",
  "url": "string",
  "business_name": "string",
  "site_url": "string",
  "terms_of_service": "string",
  "modified_date": "2017-02-12T00:24:35Z",
  "has_integration": true,
  "whitelist_email_on_purchase": true,
  "whitelist_popup_on_purchase": true
}
````
````json
{}
````
<aside class="warning">
To perform this operation, you must be authenticated by means of one of the following methods:
apiKey
</aside>


# Customers

Customers methods provide access to information and operations relating to the customers.

## FindCustomers

> Code samples

````shell
# You can also use wget
curl -X get http://localhost:10010/V1/customers/
````

````http
GET http://localhost:10010/V1/customers/ HTTP/1.1
Host: localhost:10010
Content-Type: application/json
Accept: application/json
````

````html
<script>
  $.ajax({
    url: 'http://localhost:10010/V1/customers/',
    method: 'get',
    success: function(data) {
      console.log(JSON.stringify(data));
    }
  })
</script>
````

````javascript
const request = require('node-fetch');
fetch('http://localhost:10010/V1/customers/', { method: 'GET'})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});
````

````ruby
require 'rest-client'
require 'json'

result = RestClient.get 'http://localhost:10010/V1/customers/', params:
  {
    # TODO
  }

p JSON.parse(result)
````

````python
import requests

r = requests.get('http://localhost:10010/V1/customers/', params={
  # TODO
})

print r.json()
````

````java
URL obj = new URL("http://localhost:10010/V1/customers/");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());
````

`GET /customers/`

*Retrieve all customers*

Retrieve all customers

### Responses

Status|Meaning|Description
---|---|---|
200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|Customer object response
default|Default|Error

> Example responses

````json
[
  {
    "_key": "string",
    "address1": "string",
    "address2": "string",
    "area_code": "string",
    "city": "string",
    "company": "string",
    "country": "string",
    "email": "string",
    "first_name": "string",
    "last_name": "string",
    "modified_date": "2017-02-12T00:24:35Z",
    "orders_count": 0,
    "phone": "string",
    "province": "string",
    "ref_id": "string",
    "signed_up_at": "2017-02-12T00:24:35Z",
    "time_zone_dst_offset": 0,
    "time_zone_id": "string",
    "time_zone_raw_offset": "string",
    "total_spent": 0,
    "user_id": "string",
    "valid_phone_number": true,
    "verified": true,
    "zip": "string"
  }
]
````
````json
{}
````
<aside class="warning">
To perform this operation, you must be authenticated by means of one of the following methods:
apiKey
</aside>


## CreateOrUpdateCustomer

> Code samples

````shell
# You can also use wget
curl -X post http://localhost:10010/V1/customers/
````

````http
POST http://localhost:10010/V1/customers/ HTTP/1.1
Host: localhost:10010
Content-Type: application/json
Accept: application/json
````

````html
<script>
  $.ajax({
    url: 'http://localhost:10010/V1/customers/',
    method: 'post',
    success: function(data) {
      console.log(JSON.stringify(data));
    }
  })
</script>
````

````javascript
const request = require('node-fetch');
fetch('http://localhost:10010/V1/customers/', { method: 'POST'})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});
````

````ruby
require 'rest-client'
require 'json'

result = RestClient.post 'http://localhost:10010/V1/customers/', params:
  {
    # TODO
  }

p JSON.parse(result)
````

````python
import requests

r = requests.post('http://localhost:10010/V1/customers/', params={
  # TODO
})

print r.json()
````

````java
URL obj = new URL("http://localhost:10010/V1/customers/");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("POST");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());
````

`POST /customers/`

*Create or Update a customer*

Create or Update a customer

### Parameters

Parameter|In|Type|Required|Description
---|---|---|---|---|
customer|body|Customer|true|Add or update customer details



> Body parameter

````json
{
  "_key": "string",
  "address1": "string",
  "address2": "string",
  "area_code": "string",
  "city": "string",
  "company": "string",
  "country": "string",
  "email": "string",
  "first_name": "string",
  "last_name": "string",
  "modified_date": "2017-02-12T00:24:35Z",
  "orders_count": 0,
  "phone": "string",
  "province": "string",
  "ref_id": "string",
  "signed_up_at": "2017-02-12T00:24:35Z",
  "time_zone_dst_offset": 0,
  "time_zone_id": "string",
  "time_zone_raw_offset": "string",
  "total_spent": 0,
  "user_id": "string",
  "valid_phone_number": true,
  "verified": true,
  "zip": "string"
}
````
### Responses

Status|Meaning|Description
---|---|---|
200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|Store response
default|Default|Error

> Example responses

````json
[
  {
    "_key": "string",
    "address1": "string",
    "address2": "string",
    "area_code": "string",
    "city": "string",
    "company": "string",
    "country": "string",
    "email": "string",
    "first_name": "string",
    "last_name": "string",
    "modified_date": "2017-02-12T00:24:35Z",
    "orders_count": 0,
    "phone": "string",
    "province": "string",
    "ref_id": "string",
    "signed_up_at": "2017-02-12T00:24:35Z",
    "time_zone_dst_offset": 0,
    "time_zone_id": "string",
    "time_zone_raw_offset": "string",
    "total_spent": 0,
    "user_id": "string",
    "valid_phone_number": true,
    "verified": true,
    "zip": "string"
  }
]
````
````json
{}
````
<aside class="warning">
To perform this operation, you must be authenticated by means of one of the following methods:
apiKey
</aside>


## FindCustomersById

> Code samples

````shell
# You can also use wget
curl -X get http://localhost:10010/V1/customers/{id}
````

````http
GET http://localhost:10010/V1/customers/{id} HTTP/1.1
Host: localhost:10010
Content-Type: application/json
Accept: application/json
````

````html
<script>
  $.ajax({
    url: 'http://localhost:10010/V1/customers/{id}',
    method: 'get',
    success: function(data) {
      console.log(JSON.stringify(data));
    }
  })
</script>
````

````javascript
const request = require('node-fetch');
fetch('http://localhost:10010/V1/customers/{id}', { method: 'GET'})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});
````

````ruby
require 'rest-client'
require 'json'

result = RestClient.get 'http://localhost:10010/V1/customers/{id}', params:
  {
    # TODO
  }

p JSON.parse(result)
````

````python
import requests

r = requests.get('http://localhost:10010/V1/customers/{id}', params={
  # TODO
})

print r.json()
````

````java
URL obj = new URL("http://localhost:10010/V1/customers/{id}");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());
````

`GET /customers/{id}`

*Retrieve a single customer by id*

Retrieve a single customer by id

### Parameters

Parameter|In|Type|Required|Description
---|---|---|---|---|
id|path|string|true|ID of the customer to get



### Responses

Status|Meaning|Description
---|---|---|
200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|Customer object response
default|Default|Error

> Example responses

````json
{
  "_key": "string",
  "address1": "string",
  "address2": "string",
  "area_code": "string",
  "city": "string",
  "company": "string",
  "country": "string",
  "email": "string",
  "first_name": "string",
  "last_name": "string",
  "modified_date": "2017-02-12T00:24:35Z",
  "orders_count": 0,
  "phone": "string",
  "province": "string",
  "ref_id": "string",
  "signed_up_at": "2017-02-12T00:24:35Z",
  "time_zone_dst_offset": 0,
  "time_zone_id": "string",
  "time_zone_raw_offset": "string",
  "total_spent": 0,
  "user_id": "string",
  "valid_phone_number": true,
  "verified": true,
  "zip": "string"
}
````
````json
{}
````
<aside class="warning">
To perform this operation, you must be authenticated by means of one of the following methods:
apiKey
</aside>


# Products

Products methods provide access to information and operations relating to the products.

## FindProducts

> Code samples

````shell
# You can also use wget
curl -X get http://localhost:10010/V1/products/
````

````http
GET http://localhost:10010/V1/products/ HTTP/1.1
Host: localhost:10010
Content-Type: application/json
Accept: application/json
````

````html
<script>
  $.ajax({
    url: 'http://localhost:10010/V1/products/',
    method: 'get',
    success: function(data) {
      console.log(JSON.stringify(data));
    }
  })
</script>
````

````javascript
const request = require('node-fetch');
fetch('http://localhost:10010/V1/products/', { method: 'GET'})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});
````

````ruby
require 'rest-client'
require 'json'

result = RestClient.get 'http://localhost:10010/V1/products/', params:
  {
    # TODO
  }

p JSON.parse(result)
````

````python
import requests

r = requests.get('http://localhost:10010/V1/products/', params={
  # TODO
})

print r.json()
````

````java
URL obj = new URL("http://localhost:10010/V1/products/");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());
````

`GET /products/`

*Retrieve all products*

Retrieve all products

### Responses

Status|Meaning|Description
---|---|---|
200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|Product object response
default|Default|Error

> Example responses

````json
[
  {
    "_key": "string",
    "categories": "string",
    "currency": "string",
    "handle": "string",
    "image_source_url": "string",
    "image_thubnail": "string",
    "is_downloadable": true,
    "is_virtual": true,
    "keyword_locked": true,
    "out_stock": true,
    "price": 0,
    "price_compare": 0,
    "product_tags": [
      "string"
    ],
    "published_at": "2017-02-12T00:24:35Z",
    "ref_id": "string",
    "sku": "string",
    "source": "string",
    "tags": "string",
    "title": "string",
    "type": "string",
    "user_id": "string",
    "variants": [
      {
        "attributes": [
          {
            "name": "string",
            "option": "string",
            "slug": "string"
          }
        ],
        "created": "2017-02-12T00:24:35Z",
        "image_source_url": "string",
        "in_stock": true,
        "inventory_management": "string",
        "inventory_quantity": "string",
        "price": 0,
        "price_compare": 0,
        "product_ref_id": "string",
        "ref_id": "string",
        "sku": "string",
        "taxable": true,
        "title": "string",
        "updated": "2017-02-12T00:24:35Z",
        "visible": true,
        "weight": 0
      }
    ],
    "vendor": "string"
  }
]
````
````json
{}
````
<aside class="warning">
To perform this operation, you must be authenticated by means of one of the following methods:
apiKey
</aside>


## CreateOrUpdateProduct

> Code samples

````shell
# You can also use wget
curl -X post http://localhost:10010/V1/products/
````

````http
POST http://localhost:10010/V1/products/ HTTP/1.1
Host: localhost:10010
Content-Type: application/json
Accept: application/json
````

````html
<script>
  $.ajax({
    url: 'http://localhost:10010/V1/products/',
    method: 'post',
    success: function(data) {
      console.log(JSON.stringify(data));
    }
  })
</script>
````

````javascript
const request = require('node-fetch');
fetch('http://localhost:10010/V1/products/', { method: 'POST'})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});
````

````ruby
require 'rest-client'
require 'json'

result = RestClient.post 'http://localhost:10010/V1/products/', params:
  {
    # TODO
  }

p JSON.parse(result)
````

````python
import requests

r = requests.post('http://localhost:10010/V1/products/', params={
  # TODO
})

print r.json()
````

````java
URL obj = new URL("http://localhost:10010/V1/products/");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("POST");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());
````

`POST /products/`

*Create or Update a product*

Create or Update a product

### Parameters

Parameter|In|Type|Required|Description
---|---|---|---|---|
product|body|Product|true|Add or update products details



> Body parameter

````json
{
  "_key": "string",
  "categories": "string",
  "currency": "string",
  "handle": "string",
  "image_source_url": "string",
  "image_thubnail": "string",
  "is_downloadable": true,
  "is_virtual": true,
  "keyword_locked": true,
  "out_stock": true,
  "price": 0,
  "price_compare": 0,
  "product_tags": [
    "string"
  ],
  "published_at": "2017-02-12T00:24:35Z",
  "ref_id": "string",
  "sku": "string",
  "source": "string",
  "tags": "string",
  "title": "string",
  "type": "string",
  "user_id": "string",
  "variants": [
    {
      "attributes": [
        {
          "name": "string",
          "option": "string",
          "slug": "string"
        }
      ],
      "created": "2017-02-12T00:24:35Z",
      "image_source_url": "string",
      "in_stock": true,
      "inventory_management": "string",
      "inventory_quantity": "string",
      "price": 0,
      "price_compare": 0,
      "product_ref_id": "string",
      "ref_id": "string",
      "sku": "string",
      "taxable": true,
      "title": "string",
      "updated": "2017-02-12T00:24:35Z",
      "visible": true,
      "weight": 0
    }
  ],
  "vendor": "string"
}
````
### Responses

Status|Meaning|Description
---|---|---|
200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|Store response
default|Default|Error

> Example responses

````json
[
  {
    "_key": "string",
    "categories": "string",
    "currency": "string",
    "handle": "string",
    "image_source_url": "string",
    "image_thubnail": "string",
    "is_downloadable": true,
    "is_virtual": true,
    "keyword_locked": true,
    "out_stock": true,
    "price": 0,
    "price_compare": 0,
    "product_tags": [
      "string"
    ],
    "published_at": "2017-02-12T00:24:35Z",
    "ref_id": "string",
    "sku": "string",
    "source": "string",
    "tags": "string",
    "title": "string",
    "type": "string",
    "user_id": "string",
    "variants": [
      {
        "attributes": [
          {
            "name": "string",
            "option": "string",
            "slug": "string"
          }
        ],
        "created": "2017-02-12T00:24:35Z",
        "image_source_url": "string",
        "in_stock": true,
        "inventory_management": "string",
        "inventory_quantity": "string",
        "price": 0,
        "price_compare": 0,
        "product_ref_id": "string",
        "ref_id": "string",
        "sku": "string",
        "taxable": true,
        "title": "string",
        "updated": "2017-02-12T00:24:35Z",
        "visible": true,
        "weight": 0
      }
    ],
    "vendor": "string"
  }
]
````
````json
{}
````
<aside class="warning">
To perform this operation, you must be authenticated by means of one of the following methods:
apiKey
</aside>


## FindProductsById

> Code samples

````shell
# You can also use wget
curl -X get http://localhost:10010/V1/products/{id}
````

````http
GET http://localhost:10010/V1/products/{id} HTTP/1.1
Host: localhost:10010
Content-Type: application/json
Accept: application/json
````

````html
<script>
  $.ajax({
    url: 'http://localhost:10010/V1/products/{id}',
    method: 'get',
    success: function(data) {
      console.log(JSON.stringify(data));
    }
  })
</script>
````

````javascript
const request = require('node-fetch');
fetch('http://localhost:10010/V1/products/{id}', { method: 'GET'})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});
````

````ruby
require 'rest-client'
require 'json'

result = RestClient.get 'http://localhost:10010/V1/products/{id}', params:
  {
    # TODO
  }

p JSON.parse(result)
````

````python
import requests

r = requests.get('http://localhost:10010/V1/products/{id}', params={
  # TODO
})

print r.json()
````

````java
URL obj = new URL("http://localhost:10010/V1/products/{id}");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());
````

`GET /products/{id}`

*Retrieve a single product by id*

Retrieve a single product by id

### Parameters

Parameter|In|Type|Required|Description
---|---|---|---|---|
id|path|string|true|ID of the product to get



### Responses

Status|Meaning|Description
---|---|---|
200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|Product object response
default|Default|Error

> Example responses

````json
{
  "_key": "string",
  "categories": "string",
  "currency": "string",
  "handle": "string",
  "image_source_url": "string",
  "image_thubnail": "string",
  "is_downloadable": true,
  "is_virtual": true,
  "keyword_locked": true,
  "out_stock": true,
  "price": 0,
  "price_compare": 0,
  "product_tags": [
    "string"
  ],
  "published_at": "2017-02-12T00:24:35Z",
  "ref_id": "string",
  "sku": "string",
  "source": "string",
  "tags": "string",
  "title": "string",
  "type": "string",
  "user_id": "string",
  "variants": [
    {
      "attributes": [
        {
          "name": "string",
          "option": "string",
          "slug": "string"
        }
      ],
      "created": "2017-02-12T00:24:35Z",
      "image_source_url": "string",
      "in_stock": true,
      "inventory_management": "string",
      "inventory_quantity": "string",
      "price": 0,
      "price_compare": 0,
      "product_ref_id": "string",
      "ref_id": "string",
      "sku": "string",
      "taxable": true,
      "title": "string",
      "updated": "2017-02-12T00:24:35Z",
      "visible": true,
      "weight": 0
    }
  ],
  "vendor": "string"
}
````
````json
{}
````
<aside class="warning">
To perform this operation, you must be authenticated by means of one of the following methods:
apiKey
</aside>


# Orders

Orders methods provide access to information and operations relating to the orders.

## FindOrders

> Code samples

````shell
# You can also use wget
curl -X get http://localhost:10010/V1/orders/
````

````http
GET http://localhost:10010/V1/orders/ HTTP/1.1
Host: localhost:10010
Content-Type: application/json
Accept: application/json
````

````html
<script>
  $.ajax({
    url: 'http://localhost:10010/V1/orders/',
    method: 'get',
    success: function(data) {
      console.log(JSON.stringify(data));
    }
  })
</script>
````

````javascript
const request = require('node-fetch');
fetch('http://localhost:10010/V1/orders/', { method: 'GET'})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});
````

````ruby
require 'rest-client'
require 'json'

result = RestClient.get 'http://localhost:10010/V1/orders/', params:
  {
    # TODO
  }

p JSON.parse(result)
````

````python
import requests

r = requests.get('http://localhost:10010/V1/orders/', params={
  # TODO
})

print r.json()
````

````java
URL obj = new URL("http://localhost:10010/V1/orders/");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());
````

`GET /orders/`

*Retrieve all orders*

Retrieve all orders

### Responses

Status|Meaning|Description
---|---|---|
200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|Order object response
default|Default|Error

> Example responses

````json
[
  {
    "_key": "string",
    "customer_ref_id": "string",
    "financial_status": "string",
    "iqx_order": "string",
    "line_items": [
      {
        "attributes": [
          {
            "fulfillable_quantity": 0,
            "price": 0,
            "product_ref_id": 0,
            "ref_id": 0,
            "sku": "string"
          }
        ]
      }
    ],
    "processed_at": "2017-02-12T00:24:35Z",
    "ref_id": 0,
    "subtotal_price": 0,
    "total_price": 0,
    "total_shipping": 0,
    "total_tax": 0,
    "user_id": "string"
  }
]
````
````json
{}
````
<aside class="warning">
To perform this operation, you must be authenticated by means of one of the following methods:
apiKey
</aside>


## CreateOrUpdateOrder

> Code samples

````shell
# You can also use wget
curl -X post http://localhost:10010/V1/orders/
````

````http
POST http://localhost:10010/V1/orders/ HTTP/1.1
Host: localhost:10010
Content-Type: application/json
Accept: application/json
````

````html
<script>
  $.ajax({
    url: 'http://localhost:10010/V1/orders/',
    method: 'post',
    success: function(data) {
      console.log(JSON.stringify(data));
    }
  })
</script>
````

````javascript
const request = require('node-fetch');
fetch('http://localhost:10010/V1/orders/', { method: 'POST'})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});
````

````ruby
require 'rest-client'
require 'json'

result = RestClient.post 'http://localhost:10010/V1/orders/', params:
  {
    # TODO
  }

p JSON.parse(result)
````

````python
import requests

r = requests.post('http://localhost:10010/V1/orders/', params={
  # TODO
})

print r.json()
````

````java
URL obj = new URL("http://localhost:10010/V1/orders/");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("POST");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());
````

`POST /orders/`

*Create or Update a order*

Create or Update a order

### Parameters

Parameter|In|Type|Required|Description
---|---|---|---|---|
order|body|Order|true|Add or update orders details



> Body parameter

````json
{
  "_key": "string",
  "customer_ref_id": "string",
  "financial_status": "string",
  "iqx_order": "string",
  "line_items": [
    {
      "attributes": [
        {
          "fulfillable_quantity": 0,
          "price": 0,
          "product_ref_id": 0,
          "ref_id": 0,
          "sku": "string"
        }
      ]
    }
  ],
  "processed_at": "2017-02-12T00:24:35Z",
  "ref_id": 0,
  "subtotal_price": 0,
  "total_price": 0,
  "total_shipping": 0,
  "total_tax": 0,
  "user_id": "string"
}
````
### Responses

Status|Meaning|Description
---|---|---|
200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|Order response
default|Default|Error

> Example responses

````json
[
  {
    "_key": "string",
    "customer_ref_id": "string",
    "financial_status": "string",
    "iqx_order": "string",
    "line_items": [
      {
        "attributes": [
          {
            "fulfillable_quantity": 0,
            "price": 0,
            "product_ref_id": 0,
            "ref_id": 0,
            "sku": "string"
          }
        ]
      }
    ],
    "processed_at": "2017-02-12T00:24:35Z",
    "ref_id": 0,
    "subtotal_price": 0,
    "total_price": 0,
    "total_shipping": 0,
    "total_tax": 0,
    "user_id": "string"
  }
]
````
````json
{}
````
<aside class="warning">
To perform this operation, you must be authenticated by means of one of the following methods:
apiKey
</aside>


## FindOrdersById

> Code samples

````shell
# You can also use wget
curl -X get http://localhost:10010/V1/orders/{id}
````

````http
GET http://localhost:10010/V1/orders/{id} HTTP/1.1
Host: localhost:10010
Content-Type: application/json
Accept: application/json
````

````html
<script>
  $.ajax({
    url: 'http://localhost:10010/V1/orders/{id}',
    method: 'get',
    success: function(data) {
      console.log(JSON.stringify(data));
    }
  })
</script>
````

````javascript
const request = require('node-fetch');
fetch('http://localhost:10010/V1/orders/{id}', { method: 'GET'})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});
````

````ruby
require 'rest-client'
require 'json'

result = RestClient.get 'http://localhost:10010/V1/orders/{id}', params:
  {
    # TODO
  }

p JSON.parse(result)
````

````python
import requests

r = requests.get('http://localhost:10010/V1/orders/{id}', params={
  # TODO
})

print r.json()
````

````java
URL obj = new URL("http://localhost:10010/V1/orders/{id}");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());
````

`GET /orders/{id}`

*Retrieve a single order by id*

Retrieve a single order by id

### Parameters

Parameter|In|Type|Required|Description
---|---|---|---|---|
id|path|string|true|ID of the order to get



### Responses

Status|Meaning|Description
---|---|---|
200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|Order object response
default|Default|Error

> Example responses

````json
{
  "_key": "string",
  "customer_ref_id": "string",
  "financial_status": "string",
  "iqx_order": "string",
  "line_items": [
    {
      "attributes": [
        {
          "fulfillable_quantity": 0,
          "price": 0,
          "product_ref_id": 0,
          "ref_id": 0,
          "sku": "string"
        }
      ]
    }
  ],
  "processed_at": "2017-02-12T00:24:35Z",
  "ref_id": 0,
  "subtotal_price": 0,
  "total_price": 0,
  "total_shipping": 0,
  "total_tax": 0,
  "user_id": "string"
}
````
````json
{}
````
<aside class="warning">
To perform this operation, you must be authenticated by means of one of the following methods:
apiKey
</aside>


# Events

Events methods provide access to information and operations relating to the events.

## FindEvents

> Code samples

````shell
# You can also use wget
curl -X get http://localhost:10010/V1/events/
````

````http
GET http://localhost:10010/V1/events/ HTTP/1.1
Host: localhost:10010
Content-Type: application/json
Accept: application/json
````

````html
<script>
  $.ajax({
    url: 'http://localhost:10010/V1/events/',
    method: 'get',
    success: function(data) {
      console.log(JSON.stringify(data));
    }
  })
</script>
````

````javascript
const request = require('node-fetch');
fetch('http://localhost:10010/V1/events/', { method: 'GET'})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});
````

````ruby
require 'rest-client'
require 'json'

result = RestClient.get 'http://localhost:10010/V1/events/', params:
  {
    # TODO
  }

p JSON.parse(result)
````

````python
import requests

r = requests.get('http://localhost:10010/V1/events/', params={
  # TODO
})

print r.json()
````

````java
URL obj = new URL("http://localhost:10010/V1/events/");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());
````

`GET /events/`

*Retrieve all events*

Retrieve all events

### Responses

Status|Meaning|Description
---|---|---|
200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|Event object response
default|Default|Error

> Example responses

````json
[
  {
    "_key": "string",
    "name": "string",
    "description": "string",
    "status": "string",
    "type": "string",
    "event_start_date": "2017-02-12T00:24:35Z",
    "event_end_date": "2017-02-12T00:24:35Z",
    "door_open_time": "2017-02-12T00:24:35Z",
    "door_close_time": "2017-02-12T00:24:35Z",
    "total_capacity": 0,
    "purchase_limit": 0,
    "event_url": "string",
    "currency": "string",
    "tickets": [
      {
        "_key": "string",
        "name": "string",
        "description": "string",
        "ticket_url": "string",
        "order": 0,
        "price": 0,
        "maximum_available": 0,
        "availability": {
          "date_restrictions_status": true,
          "date_restrictions_Start_date": "string",
          "date_restrictions_end_date": "string",
          "date_restrictions_Start_time": "string",
          "date_restrictions_end_time": "string"
        },
        "modified_date": "2017-02-12T00:24:35Z",
        "user_id": "string"
      }
    ],
    "time_zone": "string",
    "artist_name": "string",
    "venue": {
      "name": "string",
      "address": "string",
      "city": "string",
      "province": "string",
      "country": "string",
      "zip": "string"
    },
    "scanner_code": "string",
    "modified_date": "2017-02-12T00:24:35Z",
    "user_id": "string"
  }
]
````
````json
{}
````
<aside class="warning">
To perform this operation, you must be authenticated by means of one of the following methods:
apiKey
</aside>


## CreateOrUpdateEvent

> Code samples

````shell
# You can also use wget
curl -X post http://localhost:10010/V1/events/
````

````http
POST http://localhost:10010/V1/events/ HTTP/1.1
Host: localhost:10010
Content-Type: application/json
Accept: application/json
````

````html
<script>
  $.ajax({
    url: 'http://localhost:10010/V1/events/',
    method: 'post',
    success: function(data) {
      console.log(JSON.stringify(data));
    }
  })
</script>
````

````javascript
const request = require('node-fetch');
fetch('http://localhost:10010/V1/events/', { method: 'POST'})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});
````

````ruby
require 'rest-client'
require 'json'

result = RestClient.post 'http://localhost:10010/V1/events/', params:
  {
    # TODO
  }

p JSON.parse(result)
````

````python
import requests

r = requests.post('http://localhost:10010/V1/events/', params={
  # TODO
})

print r.json()
````

````java
URL obj = new URL("http://localhost:10010/V1/events/");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("POST");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());
````

`POST /events/`

*Create or Update a event*

Create or Update a event

### Parameters

Parameter|In|Type|Required|Description
---|---|---|---|---|
event|body|Event|true|Add or update events details



> Body parameter

````json
{
  "_key": "string",
  "name": "string",
  "description": "string",
  "status": "string",
  "type": "string",
  "event_start_date": "2017-02-12T00:24:35Z",
  "event_end_date": "2017-02-12T00:24:35Z",
  "door_open_time": "2017-02-12T00:24:35Z",
  "door_close_time": "2017-02-12T00:24:35Z",
  "total_capacity": 0,
  "purchase_limit": 0,
  "event_url": "string",
  "currency": "string",
  "tickets": [
    {
      "_key": "string",
      "name": "string",
      "description": "string",
      "ticket_url": "string",
      "order": 0,
      "price": 0,
      "maximum_available": 0,
      "availability": {
        "date_restrictions_status": true,
        "date_restrictions_Start_date": "string",
        "date_restrictions_end_date": "string",
        "date_restrictions_Start_time": "string",
        "date_restrictions_end_time": "string"
      },
      "modified_date": "2017-02-12T00:24:35Z",
      "user_id": "string"
    }
  ],
  "time_zone": "string",
  "artist_name": "string",
  "venue": {
    "name": "string",
    "address": "string",
    "city": "string",
    "province": "string",
    "country": "string",
    "zip": "string"
  },
  "scanner_code": "string",
  "modified_date": "2017-02-12T00:24:35Z",
  "user_id": "string"
}
````
### Responses

Status|Meaning|Description
---|---|---|
200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|Event response
default|Default|Error

> Example responses

````json
[
  {
    "_key": "string",
    "name": "string",
    "description": "string",
    "status": "string",
    "type": "string",
    "event_start_date": "2017-02-12T00:24:35Z",
    "event_end_date": "2017-02-12T00:24:35Z",
    "door_open_time": "2017-02-12T00:24:35Z",
    "door_close_time": "2017-02-12T00:24:35Z",
    "total_capacity": 0,
    "purchase_limit": 0,
    "event_url": "string",
    "currency": "string",
    "tickets": [
      {
        "_key": "string",
        "name": "string",
        "description": "string",
        "ticket_url": "string",
        "order": 0,
        "price": 0,
        "maximum_available": 0,
        "availability": {
          "date_restrictions_status": true,
          "date_restrictions_Start_date": "string",
          "date_restrictions_end_date": "string",
          "date_restrictions_Start_time": "string",
          "date_restrictions_end_time": "string"
        },
        "modified_date": "2017-02-12T00:24:35Z",
        "user_id": "string"
      }
    ],
    "time_zone": "string",
    "artist_name": "string",
    "venue": {
      "name": "string",
      "address": "string",
      "city": "string",
      "province": "string",
      "country": "string",
      "zip": "string"
    },
    "scanner_code": "string",
    "modified_date": "2017-02-12T00:24:35Z",
    "user_id": "string"
  }
]
````
````json
{}
````
<aside class="warning">
To perform this operation, you must be authenticated by means of one of the following methods:
apiKey
</aside>


## FindEventsById

> Code samples

````shell
# You can also use wget
curl -X get http://localhost:10010/V1/events/{id}
````

````http
GET http://localhost:10010/V1/events/{id} HTTP/1.1
Host: localhost:10010
Content-Type: application/json
Accept: application/json
````

````html
<script>
  $.ajax({
    url: 'http://localhost:10010/V1/events/{id}',
    method: 'get',
    success: function(data) {
      console.log(JSON.stringify(data));
    }
  })
</script>
````

````javascript
const request = require('node-fetch');
fetch('http://localhost:10010/V1/events/{id}', { method: 'GET'})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});
````

````ruby
require 'rest-client'
require 'json'

result = RestClient.get 'http://localhost:10010/V1/events/{id}', params:
  {
    # TODO
  }

p JSON.parse(result)
````

````python
import requests

r = requests.get('http://localhost:10010/V1/events/{id}', params={
  # TODO
})

print r.json()
````

````java
URL obj = new URL("http://localhost:10010/V1/events/{id}");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());
````

`GET /events/{id}`

*Retrieve a single event by id*

Retrieve a single event by id

### Parameters

Parameter|In|Type|Required|Description
---|---|---|---|---|
id|path|string|true|ID of the event to get



### Responses

Status|Meaning|Description
---|---|---|
200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|Event object response
default|Default|Error

> Example responses

````json
{
  "_key": "string",
  "name": "string",
  "description": "string",
  "status": "string",
  "type": "string",
  "event_start_date": "2017-02-12T00:24:35Z",
  "event_end_date": "2017-02-12T00:24:35Z",
  "door_open_time": "2017-02-12T00:24:35Z",
  "door_close_time": "2017-02-12T00:24:35Z",
  "total_capacity": 0,
  "purchase_limit": 0,
  "event_url": "string",
  "currency": "string",
  "tickets": [
    {
      "_key": "string",
      "name": "string",
      "description": "string",
      "ticket_url": "string",
      "order": 0,
      "price": 0,
      "maximum_available": 0,
      "availability": {
        "date_restrictions_status": true,
        "date_restrictions_Start_date": "string",
        "date_restrictions_end_date": "string",
        "date_restrictions_Start_time": "string",
        "date_restrictions_end_time": "string"
      },
      "modified_date": "2017-02-12T00:24:35Z",
      "user_id": "string"
    }
  ],
  "time_zone": "string",
  "artist_name": "string",
  "venue": {
    "name": "string",
    "address": "string",
    "city": "string",
    "province": "string",
    "country": "string",
    "zip": "string"
  },
  "scanner_code": "string",
  "modified_date": "2017-02-12T00:24:35Z",
  "user_id": "string"
}
````
````json
{}
````
<aside class="success">
This operation does not require authentication
</aside>

# Event Tickets

Event Tickets methods provide access to information and operations relating to the event tickets.

## FindEventTickets

> Code samples

````shell
# You can also use wget
curl -X get http://localhost:10010/V1/events/{id}/tickets/
````

````http
GET http://localhost:10010/V1/events/{id}/tickets/ HTTP/1.1
Host: localhost:10010
Content-Type: application/json
Accept: application/json
````

````html
<script>
  $.ajax({
    url: 'http://localhost:10010/V1/events/{id}/tickets/',
    method: 'get',
    success: function(data) {
      console.log(JSON.stringify(data));
    }
  })
</script>
````

````javascript
const request = require('node-fetch');
fetch('http://localhost:10010/V1/events/{id}/tickets/', { method: 'GET'})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});
````

````ruby
require 'rest-client'
require 'json'

result = RestClient.get 'http://localhost:10010/V1/events/{id}/tickets/', params:
  {
    # TODO
  }

p JSON.parse(result)
````

````python
import requests

r = requests.get('http://localhost:10010/V1/events/{id}/tickets/', params={
  # TODO
})

print r.json()
````

````java
URL obj = new URL("http://localhost:10010/V1/events/{id}/tickets/");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());
````

`GET /events/{id}/tickets/`

*Retrieve all tickets for an event*

Retrieve all tickets for an event

### Parameters

Parameter|In|Type|Required|Description
---|---|---|---|---|
id|path|string|true|ID of the event to get



### Responses

Status|Meaning|Description
---|---|---|
200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|Event Tickets object response
default|Default|Error

> Example responses

````json
[
  {
    "_key": "string",
    "name": "string",
    "description": "string",
    "ticket_url": "string",
    "order": 0,
    "price": 0,
    "maximum_available": 0,
    "availability": {
      "date_restrictions_status": true,
      "date_restrictions_Start_date": "string",
      "date_restrictions_end_date": "string",
      "date_restrictions_Start_time": "string",
      "date_restrictions_end_time": "string"
    },
    "modified_date": "2017-02-12T00:24:35Z",
    "user_id": "string"
  }
]
````
````json
{}
````
<aside class="warning">
To perform this operation, you must be authenticated by means of one of the following methods:
apiKey
</aside>


## CreateOrUpdateEventTicket

> Code samples

````shell
# You can also use wget
curl -X post http://localhost:10010/V1/events/{id}/tickets/
````

````http
POST http://localhost:10010/V1/events/{id}/tickets/ HTTP/1.1
Host: localhost:10010
Content-Type: application/json
Accept: application/json
````

````html
<script>
  $.ajax({
    url: 'http://localhost:10010/V1/events/{id}/tickets/',
    method: 'post',
    success: function(data) {
      console.log(JSON.stringify(data));
    }
  })
</script>
````

````javascript
const request = require('node-fetch');
fetch('http://localhost:10010/V1/events/{id}/tickets/', { method: 'POST'})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});
````

````ruby
require 'rest-client'
require 'json'

result = RestClient.post 'http://localhost:10010/V1/events/{id}/tickets/', params:
  {
    # TODO
  }

p JSON.parse(result)
````

````python
import requests

r = requests.post('http://localhost:10010/V1/events/{id}/tickets/', params={
  # TODO
})

print r.json()
````

````java
URL obj = new URL("http://localhost:10010/V1/events/{id}/tickets/");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("POST");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());
````

`POST /events/{id}/tickets/`

*Create or Update a event ticket*

Create or Update a event ticket

### Parameters

Parameter|In|Type|Required|Description
---|---|---|---|---|
event tickets|body|EventTicket|true|Add or update events details
id|path|string|true|ID of the event to get



> Body parameter

````json
{
  "_key": "string",
  "name": "string",
  "description": "string",
  "ticket_url": "string",
  "order": 0,
  "price": 0,
  "maximum_available": 0,
  "availability": {
    "date_restrictions_status": true,
    "date_restrictions_Start_date": "string",
    "date_restrictions_end_date": "string",
    "date_restrictions_Start_time": "string",
    "date_restrictions_end_time": "string"
  },
  "modified_date": "2017-02-12T00:24:35Z",
  "user_id": "string"
}
````
### Responses

Status|Meaning|Description
---|---|---|
200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|Event Ticket response
default|Default|Error

> Example responses

````json
[
  {
    "_key": "string",
    "name": "string",
    "description": "string",
    "ticket_url": "string",
    "order": 0,
    "price": 0,
    "maximum_available": 0,
    "availability": {
      "date_restrictions_status": true,
      "date_restrictions_Start_date": "string",
      "date_restrictions_end_date": "string",
      "date_restrictions_Start_time": "string",
      "date_restrictions_end_time": "string"
    },
    "modified_date": "2017-02-12T00:24:35Z",
    "user_id": "string"
  }
]
````
````json
{}
````
<aside class="warning">
To perform this operation, you must be authenticated by means of one of the following methods:
apiKey
</aside>


## FindEventTicketsById

> Code samples

````shell
# You can also use wget
curl -X get http://localhost:10010/V1/events/{id}/tickets/{tickets_id}/
````

````http
GET http://localhost:10010/V1/events/{id}/tickets/{tickets_id}/ HTTP/1.1
Host: localhost:10010
Content-Type: application/json
Accept: application/json
````

````html
<script>
  $.ajax({
    url: 'http://localhost:10010/V1/events/{id}/tickets/{tickets_id}/',
    method: 'get',
    success: function(data) {
      console.log(JSON.stringify(data));
    }
  })
</script>
````

````javascript
const request = require('node-fetch');
fetch('http://localhost:10010/V1/events/{id}/tickets/{tickets_id}/', { method: 'GET'})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});
````

````ruby
require 'rest-client'
require 'json'

result = RestClient.get 'http://localhost:10010/V1/events/{id}/tickets/{tickets_id}/', params:
  {
    # TODO
  }

p JSON.parse(result)
````

````python
import requests

r = requests.get('http://localhost:10010/V1/events/{id}/tickets/{tickets_id}/', params={
  # TODO
})

print r.json()
````

````java
URL obj = new URL("http://localhost:10010/V1/events/{id}/tickets/{tickets_id}/");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());
````

`GET /events/{id}/tickets/{tickets_id}/`

*Retrieve a single event ticket by id*

Retrieve a single event ticket by id

### Parameters

Parameter|In|Type|Required|Description
---|---|---|---|---|
id|path|string|true|ID of the event to get
tickets_id|path|string|true|ID of the event ticket to get



### Responses

Status|Meaning|Description
---|---|---|
200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|Event Ticket object response
default|Default|Error

> Example responses

````json
{
  "_key": "string",
  "name": "string",
  "description": "string",
  "ticket_url": "string",
  "order": 0,
  "price": 0,
  "maximum_available": 0,
  "availability": {
    "date_restrictions_status": true,
    "date_restrictions_Start_date": "string",
    "date_restrictions_end_date": "string",
    "date_restrictions_Start_time": "string",
    "date_restrictions_end_time": "string"
  },
  "modified_date": "2017-02-12T00:24:35Z",
  "user_id": "string"
}
````
````json
{}
````
<aside class="warning">
To perform this operation, you must be authenticated by means of one of the following methods:
apiKey
</aside>


# Tickets

Tickets methods provide access to information and operations relating to the tickets.

## FindTickets

> Code samples

````shell
# You can also use wget
curl -X get http://localhost:10010/V1/tickets/
````

````http
GET http://localhost:10010/V1/tickets/ HTTP/1.1
Host: localhost:10010
Content-Type: application/json
Accept: application/json
````

````html
<script>
  $.ajax({
    url: 'http://localhost:10010/V1/tickets/',
    method: 'get',
    success: function(data) {
      console.log(JSON.stringify(data));
    }
  })
</script>
````

````javascript
const request = require('node-fetch');
fetch('http://localhost:10010/V1/tickets/', { method: 'GET'})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});
````

````ruby
require 'rest-client'
require 'json'

result = RestClient.get 'http://localhost:10010/V1/tickets/', params:
  {
    # TODO
  }

p JSON.parse(result)
````

````python
import requests

r = requests.get('http://localhost:10010/V1/tickets/', params={
  # TODO
})

print r.json()
````

````java
URL obj = new URL("http://localhost:10010/V1/tickets/");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());
````

`GET /tickets/`

*Retrieve all events*

Retrieve all events

### Responses

Status|Meaning|Description
---|---|---|
200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|Event object response
default|Default|Error

> Example responses

````json
[
  {
    "_key": "string",
    "name": "string",
    "description": "string",
    "status": "string",
    "type": "string",
    "event_start_date": "2017-02-12T00:24:35Z",
    "event_end_date": "2017-02-12T00:24:35Z",
    "door_open_time": "2017-02-12T00:24:35Z",
    "door_close_time": "2017-02-12T00:24:35Z",
    "total_capacity": 0,
    "purchase_limit": 0,
    "event_url": "string",
    "currency": "string",
    "tickets": [
      {
        "_key": "string",
        "name": "string",
        "description": "string",
        "ticket_url": "string",
        "order": 0,
        "price": 0,
        "maximum_available": 0,
        "availability": {
          "date_restrictions_status": true,
          "date_restrictions_Start_date": "string",
          "date_restrictions_end_date": "string",
          "date_restrictions_Start_time": "string",
          "date_restrictions_end_time": "string"
        },
        "modified_date": "2017-02-12T00:24:35Z",
        "user_id": "string"
      }
    ],
    "time_zone": "string",
    "artist_name": "string",
    "venue": {
      "name": "string",
      "address": "string",
      "city": "string",
      "province": "string",
      "country": "string",
      "zip": "string"
    },
    "scanner_code": "string",
    "modified_date": "2017-02-12T00:24:35Z",
    "user_id": "string"
  }
]
````
````json
{}
````
<aside class="warning">
To perform this operation, you must be authenticated by means of one of the following methods:
apiKey
</aside>


## CreateOrUpdateTicket

> Code samples

````shell
# You can also use wget
curl -X post http://localhost:10010/V1/tickets/
````

````http
POST http://localhost:10010/V1/tickets/ HTTP/1.1
Host: localhost:10010
Content-Type: application/json
Accept: application/json
````

````html
<script>
  $.ajax({
    url: 'http://localhost:10010/V1/tickets/',
    method: 'post',
    success: function(data) {
      console.log(JSON.stringify(data));
    }
  })
</script>
````

````javascript
const request = require('node-fetch');
fetch('http://localhost:10010/V1/tickets/', { method: 'POST'})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});
````

````ruby
require 'rest-client'
require 'json'

result = RestClient.post 'http://localhost:10010/V1/tickets/', params:
  {
    # TODO
  }

p JSON.parse(result)
````

````python
import requests

r = requests.post('http://localhost:10010/V1/tickets/', params={
  # TODO
})

print r.json()
````

````java
URL obj = new URL("http://localhost:10010/V1/tickets/");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("POST");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());
````

`POST /tickets/`

*Create or Update a ticket*

Create or Update a ticket

### Parameters

Parameter|In|Type|Required|Description
---|---|---|---|---|
ticket|body|Ticket|true|Add or update ticket details



> Body parameter

````json
{
  "_key": "string",
  "ticket_number": "string",
  "card_number": "string",
  "event_name": "string",
  "artist_name": "string",
  "customer_ref_id": "string",
  "venue": {
    "name": "string",
    "address": "string",
    "city": "string",
    "province": "string",
    "country": "string",
    "zip": "string"
  },
  "location": {
    "lat": "string",
    "lng": "string"
  },
  "ticket_category": 0,
  "ticket_price": 0,
  "date_purchased": 0,
  "door_open_time": "2017-02-12T00:24:35Z",
  "currency": "string",
  "subtotal_price": 0,
  "total_price": 0,
  "total_shipping": 0,
  "total_fees": 0,
  "total_tax": 0,
  "customer_email": "string",
  "modified_date": "2017-02-12T00:24:35Z",
  "user_id": "string"
}
````
### Responses

Status|Meaning|Description
---|---|---|
200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|Ticket response
default|Default|Error

> Example responses

````json
[
  {
    "_key": "string",
    "ticket_number": "string",
    "card_number": "string",
    "event_name": "string",
    "artist_name": "string",
    "customer_ref_id": "string",
    "venue": {
      "name": "string",
      "address": "string",
      "city": "string",
      "province": "string",
      "country": "string",
      "zip": "string"
    },
    "location": {
      "lat": "string",
      "lng": "string"
    },
    "ticket_category": 0,
    "ticket_price": 0,
    "date_purchased": 0,
    "door_open_time": "2017-02-12T00:24:35Z",
    "currency": "string",
    "subtotal_price": 0,
    "total_price": 0,
    "total_shipping": 0,
    "total_fees": 0,
    "total_tax": 0,
    "customer_email": "string",
    "modified_date": "2017-02-12T00:24:35Z",
    "user_id": "string"
  }
]
````
````json
{}
````
<aside class="warning">
To perform this operation, you must be authenticated by means of one of the following methods:
apiKey
</aside>


## FindTicketsById

> Code samples

````shell
# You can also use wget
curl -X get http://localhost:10010/V1/tickets/{id}
````

````http
GET http://localhost:10010/V1/tickets/{id} HTTP/1.1
Host: localhost:10010
Content-Type: application/json
Accept: application/json
````

````html
<script>
  $.ajax({
    url: 'http://localhost:10010/V1/tickets/{id}',
    method: 'get',
    success: function(data) {
      console.log(JSON.stringify(data));
    }
  })
</script>
````

````javascript
const request = require('node-fetch');
fetch('http://localhost:10010/V1/tickets/{id}', { method: 'GET'})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});
````

````ruby
require 'rest-client'
require 'json'

result = RestClient.get 'http://localhost:10010/V1/tickets/{id}', params:
  {
    # TODO
  }

p JSON.parse(result)
````

````python
import requests

r = requests.get('http://localhost:10010/V1/tickets/{id}', params={
  # TODO
})

print r.json()
````

````java
URL obj = new URL("http://localhost:10010/V1/tickets/{id}");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());
````

`GET /tickets/{id}`

*Retrieve a single ticket by id*

Retrieve a single ticket by id

### Parameters

Parameter|In|Type|Required|Description
---|---|---|---|---|
id|path|string|true|ID of the ticket to get



### Responses

Status|Meaning|Description
---|---|---|
200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|Ticket object response
default|Default|Error

> Example responses

````json
{
  "_key": "string",
  "ticket_number": "string",
  "card_number": "string",
  "event_name": "string",
  "artist_name": "string",
  "customer_ref_id": "string",
  "venue": {
    "name": "string",
    "address": "string",
    "city": "string",
    "province": "string",
    "country": "string",
    "zip": "string"
  },
  "location": {
    "lat": "string",
    "lng": "string"
  },
  "ticket_category": 0,
  "ticket_price": 0,
  "date_purchased": 0,
  "door_open_time": "2017-02-12T00:24:35Z",
  "currency": "string",
  "subtotal_price": 0,
  "total_price": 0,
  "total_shipping": 0,
  "total_fees": 0,
  "total_tax": 0,
  "customer_email": "string",
  "modified_date": "2017-02-12T00:24:35Z",
  "user_id": "string"
}
````
````json
{}
````
<aside class="warning">
To perform this operation, you must be authenticated by means of one of the following methods:
apiKey
</aside>
