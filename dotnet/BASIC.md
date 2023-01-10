# This file contains the basic of .net

### 1. .Net Core

.Net core is the new Microsoft's .Net framework designed to build cross-paltform softwares. It is free, open-source, general purpose programming platform that works for Windows, MacOS, Linux, Android, iOS and more. With the use of .Net core we can create apps, wweb development, desktop applications. cloud, IoT, Machine learning models, microservices, games and many more. It is build on the concept of create once, run anywhere.

### 2. .Net Framework

The framework is a reusable design platform for software system, which provides support for code libraries and various scripting languages. Microsoft .Net framework is a software development platform for building and running Windows applications. .Net framework contains developer tools, programming languages and libraries that are used to develop desktop and web applications.

### 3. Difference between .Net Core and .Net Framework

<u>Framework</u>
.Net Core: it is cross platform, where we can create apps for Windows, Linux, MacOS, Android. iOS and more. It is based on Universal Windows Platform

.Net Framework: it is fully development framework that provides all the basic requirements for the development of applications such as UI, DB connectivity, services, APIs etc.

<u>Platform</u>
.Net Core: it is cross platform, where we can create apps for Windows, Linux, MacOS, Android. iOS and more. It is based on Universal Windows Platform

.Net Framework: it is only compatible with Windows OS only

<u>Microservices</u>
.Net Core: it supports microservices that allows a mix of technologies that can be minimalized for each microservices.

.Net Framework: it does not allow for the construction and deployment of microservices in multiple languages.

### .Net Core Architecture

![alt text](dotnet_core_arch.png ".net core architecutre")

- <b>Core CLR</b>: Core CLR is the Common Language Runtime optimized for multiplatform and cloud-based deployments. This, along with .Net Native Runtime, forms the foundation of all .Net based platforms.

- <b>.Net Native Runtime (Managed Runtime)</b>: It is also called Managed Runtime, that contains the native windows based libraries. This also contains Ahead Of Time (AOT) compilation instead of Just In Time (JIT) compilation. This improves the performance of the applications. The .Net Native Runtime and the Core CLR are the layers that contain implementations of primitive types as well as generic collections in .Net APIs.

- <b>Unified Base Class Library (Unified BCL)</b>: The Unified Base Class Library, also referred to as CoreFX, consists of the basic and fundamental classed that form the core of the .Net Core platform.

- <b>App Models</b>: App Models is on the top of the UBCL layer. It leverage developers to develop platform-specific applications.

### What is an IL code or Intermediate Language
