# Terminology

**Global Interpreter Lock**: A global interpreter lock (GIL) is a mechanism used in computer-language interpreters to synchronize the execution of threads so that only one native thread (per process) can execute at a time. An interpreter that uses GIL always allows exactly one thread to execute at a time, even if run on a multi-core processor. Some popular interpreters that have GIL are CPython and Ruby MRI. [more](https://en.wikipedia.org/wiki/Global_interpreter_lock)

**Mutex - Mutual Exclusion Object**: In computer programming, a mutual exclusion object (mutex) is a program object that allows multiple program threads to share the same resource, such as file access, but not simultaneously. When a program is started, a mutex is created with a unique name. After this stage, any thread that needs the resource must lock the mutex from other threads while it is using the resource. The mutex is set to unlock when the data is no longer needed or the routine is finished. [more](https://www.webopedia.com/definitions/mutex/)

**Mutually Exclusive**: "Mutually exclusive" is a statistical term describing two or more events that cannot occur simultaneously. [more](https://www.investopedia.com/terms/m/mutuallyexclusive.asp)

**Thread**: A thread of execution is the smallest sequence of programmed instructions that can be managed independently by a scheduler, which is typically a part of the operating system. [more](https://en.wikipedia.org/wiki/Thread_(computing))
