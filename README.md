# Step-By-Step-Create-a-C-Mini-Project


`Here’s how to start a mini C# project correctly:`


### ✅ 1. Create a project

Inside your folder, run:

```
dotnet new console
```

### This will generate:

- `Program.cs`

- `<projectname>.csproj`

- Basic boilerplate code

--------------------

### ✅ 2. Run the project

Now you can do:

**`Bash Terminal`**:


```
dotnet run
```

This works because **.NET** now knows you have a project.


### 🔎 Optional: If you want a specific folder structure

Example:

```
mkdir MyMiniProject
cd MyMiniProject
dotnet new console
dotnet run
```

### ❗ If you already created files but no project

**Just run**: in bash terminal

```
dotnet new console
```

inside that folder to generate a `.csproj`.