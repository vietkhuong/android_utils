Change-Log
===============

### Release 2.0.1 ###
> 12.02.2017

- `Toaster` class has been made final with a private constructor as it is a utility class.
- `Permissions` class has been made abstract with a protected constructor.

### Release 2.0.0 ###
> 15.01.2017

- Refactored and changed `Logger` into interface and added `SimpleLogger` implementation.

### Release 1.0.1 ###
> 13.01.2017

- Changed annotation signature of `Logger.w(@NonNull String tag, @NonNull String msg, @NonNull Throwable tr)`
  to `Logger.w(@NonNull String tag, @NonNull String msg, @Nullable Throwable tr)`.

### Release 1.0.0 ###
> 15.12.2016