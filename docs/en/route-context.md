---
layout: doc
language: en
title: Route Context
---

The `RouteContext` class was added after the Blade 2.0.9 release as a contextual operation for routing. The essence is to encapsulate `Request` and `Response`, so they are the same as their APIs. Let's take a look at the list of methods included.

## Request related

- [#request()](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#request--)
- [#method()](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#method--)
- [#uri()](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#uri--)
- [#keepAlive()](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#keepAlive--)
- [#session()](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#session--)
- [#isIE()](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#session--)
- [#header(String headerName)](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#header-java.lang.String-)
- [#cookie(String name)](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#cookie-java.lang.String-)
- [#attribute(String key, Object value)](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#attribute-java.lang.String-java.lang.Object-)
- [#fromString(String paramName)](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#fromString-java.lang.String-)
- [#fromString(String paramName, String defaultValue)](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#fromString-java.lang.String-java.lang.String-)
- [#fromInt(String paramName)](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#fromInt-java.lang.String-)
- [#fromInt(String paramName, Integer defaultValue)](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#fromInt-java.lang.String-java.lang.Integer-)
- [#fromLong(String paramName)](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#fromLong-java.lang.String-)
- [#fromLong(String paramName, Long defaultValue)](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#fromLong-java.lang.String-java.lang.Long-)
- [#pathString(String paramName)](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#pathString-java.lang.String-)
- [#pathInt(String paramName)](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#pathInt-java.lang.String-)
- [#pathLong(String paramName)](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#pathLong-java.lang.String-)
- [#userAgent()](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#userAgent--)
- [#address()](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#address--)
- [#headers()](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#headers--)
- [#parameters()](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#parameters--)
- [#contentType()](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#contentType--)
- [#bodyToString()](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#bodyToString--)
- [#body()](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#body--)
- [#targetType()](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#targetType--)
- [#routeTarget()](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#routeTarget--)
- [#routeAction()](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#routeAction--)
- [#routeParameters()](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#routeParameters--)

## Response related

- [#response()](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#response--)
- [#contentType(String contentType)](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#contentType-java.lang.String-)
- [#status(int statusCode)](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#status-int-)
- [#header(String name, String value)](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#header-java.lang.String-java.lang.String-)
- [#badRequest()](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#badRequest--)
- [#render(String view)](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#render-java.lang.String-)
- [#render(ModelAndView modelAndView)](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#render-com.blade.mvc.ui.ModelAndView-)
- [#text(String text)](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#text-java.lang.String-)
- [#json(String json)](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#json-java.lang.String-)
- [#json(Object object)](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#json-java.lang.Object-)
- [#html(String html)](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#html-java.lang.String-)
- [#body(Body body)](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#body-com.blade.mvc.http.Body-)
- [#cookie(String name, String value)](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#cookie-java.lang.String-java.lang.String-)
- [#cookie(String name, String value, int maxAge)](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#cookie-java.lang.String-java.lang.String-int-)
- [#redirect(String url)](https://lets-blade.com/apidocs/com/blade/mvc/RouteContext.html#redirect-java.lang.String-)

## Reference

The source files for this class are [RouteContext.java](https://github.com/lets-blade/blade/blob/master/src/main/java/com/blade/mvc/RouteContext.java#L41), Also can refer to [Request](https://lets-blade.com/docs/request.html) and [Response](https://lets-blade.com/docs/response.html).