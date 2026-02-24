---
layout: post
title: "Scaffolding a .NET Core Web API with PowerShell"
date: 2026-02-24
---

# Scaffolding a ASP.NET Core Web API with PowerShell

In this article, I’ll show how I automated the creation of a .NET Web API using a custom PowerShell script.

## Why?

Creating the same Clean Architecture structure repeatedly wastes time and is error prone.

## The Script

```powershell
.\templates\mservice-clean-architecture-dotNET10.ps1 `
    -SolutionName 'MyCompany.MyProduct' `
    -RootPath 'C:\my-repos' `
    -CreateDbFolders:$false
```

---
You can find the full script here:<br>
👉 https://github.com/dotKapsalis/dotnet-clean-architecture-scaffold