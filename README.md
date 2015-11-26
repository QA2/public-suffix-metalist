# public-suffix-metalist

Many programs need to understand what constitutes a valid "top level domain" (TLD). Some programs also require metadata about a TLD - for instance, information about how to interact with the whois services available for a TLD.

This repository is an attempt to document the many places where hardcoded domain suffix information lives. Databases, registries, software source code, etc.  Some of these registries are publically available, while other registries may be part of closed-source programs or live in a config file maintained by a SaaS provider. All of these registries are considered in-scope for this registry.

Many domains with TLD-like semantics exist. These domains are within the scope of this list. Examples include .com, .co.uk and pvt.k12.ma.us.

The aim is to provide an easy and up to date reference which can be used to help ensure maximum compatibilty for domain suffixes. As the registration policies and use cases for domain suffixes vary, some lists may not be applicable for some domain suffixes. 

Where a registry regularly consults one or more "upstream" registries, it's helpful to document that here. It may be unnecessary to contact a registry with updated information if that registry will obtain the information from another registry in due course.

This list is inspired by Mozilla's <a href="https://publicsuffix.org/">Public Suffix List</a>; it is a list of lists which are similiar in nature and have overlapping use cases.

( This project is undoubtedly missing MANY registries which ought to be included. Pull requests are extremely welcome. ) 
