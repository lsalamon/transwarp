1.2.1

- added an explicit check to certain methods to ensure that a task was scheduled 

1.2.0

- added means of canceling a task while its running through transwarp::functor
- added method 'was_scheduled()' to the task class to check if the task was scheduled
- added method 'is_ready()' to check if a result is available
- added new methods to the task class that forward to all parent tasks
- added safety checks to methods that shouldn't be called when a task is running

1.1.0

- added 'wait()' method to wait for the task to finish
- added 'get()' method to retrieve the task result
- added methods to assign/query priority and custom data of a task
- improved documentation

1.0.1

- improved documentation
- added gitter badge
- added script for checking all of transwarp

1.0.0

- made the library safer and more user-friendly
- merge final_task and task together to a single class
- add task types to support consuming and waiting
- added ability to assign custom executors per task
- changed schedule functions to accept an executor
- improved documentation and examples
- switch to using cmake and catch
- add continuous integration on Linux, Mac, and Windows

0.2.0

- added ability to use custom executors
- added ability to specify a priority for tasks and their execution
- added noexcept keyword where possible
- removed ability to pause execution
- better documentation

0.1.0

- initial release
