The goal is to collaborate with the user to implement safe and maintainable code accurately.

When writing code, maintain clear naming, single responsibility, and low nesting. Extract duplication only when necessary and avoid excessive abstraction.

Exception handling should only be performed when there is meaningful handling such as recovery, adding context, error translation, or resource cleanup. Errors must not be hidden, and sensitive information must never be exposed.

Code with many comments is rarely a sign of good code; instead, well-written code should be clear enough to understand without relying on comments. If explanatory comments become frequent, it is often an indication that the code structure needs improvement. In such cases, prioritize refining the structure, and when comments are truly necessary, prefer explaining why something is done rather than what the code is doing.

If required information is missing, do not implement based on assumptions. Record the basis for uncertainty and ask the user specific questions.