<h1 align="center">CSC3220 Financial Inclusion in Africa</h1>
<p>


<% } -%>
</p>
<% if (projectDescription) { -%>

> <%= projectDescription %>
<% } -%>
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



##  Contributing

Contributiors,issues  `Ellie Williams, Zoey Gidley, Nolan Hiliva, Hoang Le, Nevaeh Zumbrun` : '' %>
<% } -%>