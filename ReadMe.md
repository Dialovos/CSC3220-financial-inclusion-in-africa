<h1 align="center">CSC3220 Financial Inclusion in Africa</h1>
<p>

###  [Project Description]
</p>
 
 `We used ------ dataset to analyze the financial system in multiple african countries. Our goal is to see how many citizens in each country have bank accounts. ` 

<% if (projectHomepage) { -%>

###  [Homepage](<%= https://github.com/Dialovos/CSC3220-financial-inclusion-in-africa %>)
<% } -%>
<% if (projectDemoUrl) { -%>

###  [Demo](<%= projectDemoUrl %>)
<% } -%>
<% if (projectPrerequisites && projectPrerequisites.length) { -%>

## Prerequisites

<% projectPrerequisites.map(({ name, value }) => { -%>
- <%= name %> <%= value %>
<% }) -%>
<% } -%>
<% if (installCommand) { -%>

## Install

```sh
<%= installCommand %>
```
<% } -%>
<% if (usage) { -%>

## Usage

```sh
<%= usage %>
```
<% } -%>
<% if (testCommand) { -%>

## Run tests

```sh
<%= testCommand %>
```
<% } -%>



##  Contributors

  `Ellie Williams, Zoey Gidley, Nolan Hiliva, Hoang Le, Nevaeh Zumbrun` 