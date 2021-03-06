# Introduction to bulk Office 365 Group Connect

## Summary

Being able to connect an Office 365 group to an existing SharePoint site is important if you want to modernize that site. Once connected to an Office 365 group your site can benefit from all other group connected services like Microsoft Teams, Planner etc. This also brings your "classic" site a step closer to being a like the current modern team site, which by default is connected to an Office 365 group. The process to connect an existing site to a new Office 365 group is called Office 365 Group Connect. You can Office 365 Group Connect your site from the user interface, site per site which might be good for smaller environments. However (larger) customers often want to offer a consist experience to their users and therefore want to perform a bulk Office 365 Group Connect of their sites. In the article you'll learn how to prepare for such a bulk Office 365 Group Connect and how actually make it happen.

## What does "Office 365 Group Connect" do to your site

When you "Office 365 Group Connect" your site  a number of things will happen:

- A **new** Office 365 group will be created and that group will be connected to your site collection
- A **new** modern home page will be created in your site and set as the site's home page
- The group's Owners will now be the site collection administrators
- The group's Owners will be added to your site's Owners group
- The group's Members will be added to your site's Members group

Once connected to an Office 365 group the site behaves like a modern group connected team site, so granting people permission to the connected Office 365 group will now also grant them access to the SharePoint site, a Microsoft Team can be created on top of the site, Planner can be integrated,...

## Applies to

- Office 365 Multi-Tenant (MT)

## Prerequisites

- SharePoint PnP PowerShell
- Azure PowerShell

## Solution

Solution|Author(s)
--------|---------
O365GroupConnectSite.ps1 | Bert Jansen (**Microsoft**)
validateinput.ps1 | Bert Jansen (**Microsoft**)

## Version history

Version|Date|Comments
-------|----|--------
1.0 | March 1st 2018 | Initial commit

## Disclaimer

THIS CODE IS PROVIDED AS IS WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANT ABILITY, OR NON-INFRINGEMENT.

---

## Learn more about bulk "Office 365 Group Connect"

Checkout the [Connect to an Office 365 Group](https://docs.microsoft.com/en-us/sharepoint/dev/transform/modernize-connect-to-office365-group) article on docs.microsoft.com.