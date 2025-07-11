# 🎯 dotnet-code-style

A shared `.editorconfig` for keeping consistent formatting across all your .NET projects — because clean code is happy code! ✨


---


## 🛠️ What’s Included

This repository contains:

- ✅ A fully configured `.editorconfig` file tailored for C# and .NET development
- 🧪 Optional formatting and validation helpers (coming soon)
- 📚 Guidelines for team adoption and automation


---


## 🚀 How to Use

### 1. 📥 Copy the `.editorconfig` into your project

You can manually download or use `curl`:

```bash
curl -O https://raw.githubusercontent.com/mrkoggles/dotnet-code-style/refs/heads/main/.editorconfig
```

```
your-project/
├── .editorconfig ✅
├── src/
├── tests/
└── ...
```

### 2. 🧑‍💻 Use the Style Rules

#### ✨ Option A: Use in VSCode

Install the [EditorConfig for VS Code extension](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig).

Once installed, VS Code will **automatically detect and apply** the formatting rules in `.editorconfig` when saving files.

> [!Important]
> 💡 Make sure `"editor.formatOnSave": true` is enabled in your VS Code settings for full effect!


#### ⚙️ Option B: Format from the Command Line

Use the [.NET CLI formatting tool](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-format):

```bash
dotnet format {your-solution.sln}
```