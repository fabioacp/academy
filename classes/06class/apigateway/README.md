# AWS API Gateway

- [AWS API Gateway](#aws-api-gateway)
  - [What is an API Gateway?](#what-is-an-api-gateway)
  - [What is AWS API Gateway?](#what-is-aws-api-gateway)
  - [API types](#api-types)
  - [HTTP API](#http-api)
  - [REST API](#rest-api)
  - [Authentication and Authorisation](#authentication-and-authorisation)
  - [Caching](#caching)


## What is an API Gateway?

An application usually has the goal of getting some input data, processing it and giving some output. This flow happens via application integrations with other systems that can be an user interface or a database.

One important integration pattern integrating systems and user interfaces via an [API Gateway](https://microservices.io/patterns/apigateway.html).

![](../assets/apigateway.jpg)
[API Gateway pattern](https://microservices.io/patterns/apigateway.html)


## What is AWS API Gateway?

Amazon API Gateway is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale. 

It offers a comprehensive platform for API management. API Gateway allows you to process hundreds of thousands of concurrent API calls and handles traffic management, authorisation and access control, monitoring, and API version management.

## API types

- **REST APIs**
  -  ***HTTP APIs*** are the best choice for building APIs that only require API proxy functionality. 
  -  ***REST APIs***: If your APIs require API proxy functionality and API management features in a single solution, API Gateway also offers REST APIs.
- **Websocket APIs**

![](../assets/apigw_works.png)

## HTTP API

## REST API

## Authentication and Authorisation

## Caching

