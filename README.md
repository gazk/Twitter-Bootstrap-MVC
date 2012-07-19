### Fork of Twitter Bootstrap MVC Templates

Changes include :-

[DataTables](http://datatables.net) list template

jquery [date picker](https://github.com/eternicode/bootstrap-datepicker) integration

HelperText attribute for model classes

```csharp
public class Customer
{
  [Required]
  [StringLength(50)]
  [HelperText("Enter your full name")]
  [Display(Name = "Customer Name")]
  public string Name { get; set; }
  
  [HelperText("Some default text")]
  [Display(Name = "Checkbox option")]
  public bool IsCheckbox { get; set; }
}
```

## Twitter Bootstrap MVC Templates

A set of changes to style the default MVC template to use [Twitter Bootstrap](http://twitter.github.com/bootstrap/).

It also provides some scaffolding to use the same templates for new Controller Views.

### Usage

Download from [nuget](http://nuget.org/packages/MahApps.Twitter.Bootstrap) into your solution.

### Getting started

Copy the required views from Views-Bootstrap over Views, and build some new controllers, or new views from existing controllers.

Tweak as required :)

### Contributing (or, THIS IS WRONG - FIX IT!)

I take Pull Requests, please show me what you would fix and some examples and we'll upgrade the nuget package for any appropriate changes.