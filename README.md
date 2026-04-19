# Fynxzi Utils – Roblox Username Retrieval

Fynxzi Utils allows you to easily retrieve the currently logged-in Roblox username directly from local storage within your `.exe` application.

## 📦 Requirements

* **Fynxzi Utils**
* **Newtonsoft.Json** (any version)

## 🚀 Usage

```csharp
string user = fynxziutil.System.GetUsername();
```

## 📖 Description

This method accesses Roblox local data stored on the user's system and returns the active username. It's designed to be simple, fast, and easy to integrate into any C# application.

## ⚠️ Notes

* Make sure Roblox is installed on the target system.
* Ensure your application has permission to access local storage.
* Works only if user data is available locally.

## 🛠️ Example

```csharp
using System;

class Program
{
    static void Main()
    {
        string user = fynxziutil.System.GetUsername();
        Console.WriteLine("Logged in Roblox user: " + user);
    }
}
```
