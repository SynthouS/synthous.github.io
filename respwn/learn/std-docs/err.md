# **@err**

## Constructors

### result_type
> **Variants:**
> ```spwn
> ok(value: any) -> @dict
> err(error: string) -> @dict
> ```
> _Creates a Result container (ok/err)_

## Macros

### safe_call
> ```spwn
> (func: @function, args: @array, fallback: any) -> any
> ```
> _Safely executes function, returns fallback on error_

### unwrap
> ```spwn
> (result: @dict, fallback: any) -> any
> ```
> _Extracts value or returns fallback_

### expect
> ```spwn
> (result: @dict, message: string) -> any
> ```
> _Returns value or throws custom error_