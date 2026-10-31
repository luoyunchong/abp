**English** | [简体中文](README.md)

# ABP

[![Build Status](http://vjenkins.dynu.net:5480/job/abp/badge/icon)](http://ci.volosoft.com:5480/blue/organizations/jenkins/abp/activity)
[![NuGet](https://img.shields.io/nuget/v/Volo.Abp.Core.svg?style=flat-square)](https://www.nuget.org/packages/Volo.Abp.Core)
[![NuGet Download](https://img.shields.io/nuget/dt/Volo.Abp.Core.svg?style=flat-square)](https://www.nuget.org/packages/Volo.Abp.Core)
[![MyGet (with prereleases)](https://img.shields.io/myget/abp-nightly/vpre/Volo.Abp.svg?style=flat-square)](https://docs.abp.io/en/abp/latest/Nightly-Builds)

This project is the next generation of the [ASP.NET Boilerplate](https://aspnetboilerplate.com/) web application framework. See [the announcement](https://blog.abp.io/abp/Abp-vNext-Announcement).

See the official [web site (abp.io)](https://abp.io/) for more information.

## User, role, and permission management with a separate frontend and backend
- [https://github.com/luoyunchong/abp/tree/master/samples/Microservice/modules/app-microservice](https://github.com/luoyunchong/abp/tree/master/samples/Microservice/modules/app-microservice)
- iView-based SPA adapted from MicroserviceDemo.
## Screenshots
## Sign in
![](https://pic.superbed.cn/item/5d3bd731451253d178c18d8f.png)

Demo login details are available in the [Chinese README](README.md#登录).
![](https://pic.superbed.cn/item/5d3bd9f4451253d178c1bc80.png)
## Profile: basic user information
![](https://pic.superbed.cn/item/5d3bd731451253d178c18d98.png)

## User management
![](https://ae01.alicdn.com/kf/H77457b26dcbb4d08b5d26a629d8078b7o.png)
## User management: edit a user, assign roles, and configure organization units
![](https://pic.superbed.cn/item/5d3bda8f451253d178c1c0e7.png)
## User management: configure permissions
![](https://pic.superbed.cn/item/5d3bd82f451253d178c1a06f.png)

## Role management
![](https://pic2.superbed.cn/item/5d3bd8ce451253d178c1aafb.png)
## Role management: edit a role
![](https://pic.superbed.cn/item/5d3bd9bb451253d178c1b9e6.png)
## Role management: configure permissions
![](https://ae01.alicdn.com/kf/H973c2b0a50a545808db2d0b2f75250aa3.png)

## Department management: list, add, and edit departments
![](https://pic.superbed.cn/item/5d3bd9ce451253d178c1bb73.png)

## Audit logs
![](https://pic.superbed.cn/item/5d3bda81451253d178c1c058.png)

## Audit logs: log details
![](https://pic.superbed.cn/item/5d3bda81451253d178c1c05a.png)


## Data dictionary: add and list entries
![](https://pic.superbed.cn/item/5d3bd9b5451253d178c1b997.png)
## Dictionary category management: add and list categories
![](https://pic.superbed.cn/item/5d3bd731451253d178c18d9b.png)



### Status

This project is in **preview** stage and it's not suggested to use it in production yet.

### Documentation

See the <a href="https://docs.abp.io/" target="_blank">documentation</a>.

### Development

#### Pre Requirements

- Visual Studio 2019 16.3.0+

#### Framework

Framework solution is located under the `framework` folder. It has no external dependency.

#### Modules/Templates

[Modules](modules/) and [Templates](templates/) have their own solutions and have **local references** to the framework and each other.

Visual Studio can not work properly with the local references out of the solution folder. When you open a module/sample solution in the Visual Studio, you may get some errors related to the dependencies. In this case, run the `dotnet restore` on the command prompt for the related solution's folder. You need to run it after you first open the solution or change a dependency.

### Contribution

ABP is an open source platform. Check [the contribution guide](docs/en/Contribution/Index.md) if you want to contribute to the project.
