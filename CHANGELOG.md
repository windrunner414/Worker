# Changelog
## 1.0.1
  Made changes to upgrade the pub score 

## 1.0.0
  Upgraded package Worker to be Dart2 compatible ([#14](https://github.com/Dreckr/Worker/issues/14))

## 0.5.0
  Workers and WorkerIsolates now can wait until all tasks have been completed before closing. ([#10] (https://github.com/Dreckr/Worker/issues/10))

## 0.4.0
  Streams of events have been added, giving better monitoring capabilities. ([#11](https://github.com/Dreckr/Worker/issues/11))

## 0.3.11
  Loosen stack_trace min version dependency. ([#12](https://github.com/Dreckr/Worker/issues/12))

## 0.3.10
  Support tasks that do not return. ([#8](https://github.com/Dreckr/Worker/issues/8))

## 0.3.9
  Proper error handling with stackTrace support. ([#7](https://github.com/Dreckr/Worker/issues/7))

## 0.3.8
  WorkerIsolate factory. ([#6](https://github.com/Dreckr/Worker/issues/6))

## 0.3.7
  Bug fix.

## 0.3.6
  Minor bug fix.

## 0.3.5
  Bug fix.

## 0.3.4
  Improved isolate selection and load distribution.

## 0.3.3
  Major bug fix.

## 0.3.2
  Major bug fix.

## 0.3.1
  Bug fixes.

## 0.3.0
  Work with new Isolates API.

## 0.2.2
  Minor bug fix.

## 0.2.1
  Bug fixes.

## 0.2.0
Major rewrite:

- Isolates now may handle more than one Task at the time.
- Creation of the WorkerIsolate to abstract comunication with isolates.
- 'execute' method from Worker renamed to 'handle'.
- Workers and WorkerIsolates may be closed.
- Errors are now handled properly.