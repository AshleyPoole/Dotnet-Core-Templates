# Dotnet Core Templates

This repo contains sample Dotnet Core templates that I have created.

## Installing Templates

```
dotnet new -i ./NAME_OF_TEMPLATE_DIRECTORY
```

Example usage installing the template within the `webapi` directory:

```
dotnet new -i ./webapi
```

## Uninstalling Templates

```
dotnet new -u NAME_OF_TEMPLATE
```

Example usage uninstalling the template called `ashleypoole.webapi` directory:

```
dotnet new -u ashleypoole.webapi
```

## Templates

### webapi

Full template name: `ashleypoole.webapi`

This template will construct an dotnet core 3.0 WebApi project with an placeholder health controller, along with an accompanying tests project containing Xunit, Moq and FluentAssertions package references.