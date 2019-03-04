# Rxjava
Fundamental concepts of RxJava


**[Reactive X](http://reactivex.io/intro.html)**

ReactiveX is a library for composing asynchronous and event-based programs by using observable sequences.

It extends the observer pattern to support sequences of data and/or events and adds operators that allow you to compose sequences together declaratively while abstracting away concerns about things like low-level threading, synchronization, thread-safety, concurrent data structures, and non-blocking I/O.

## Reactive Programming
ReactiveX provides a collection of operators with which you can filter, select, transform, combine, and compose Observables. This allows for efficient execution and composition.

You can think of the Observable class as a “push” equivalent to Iterable, which is a “pull.” With an Iterable, the consumer pulls values from the producer and the thread blocks until those values arrive. By contrast, with an Observable the producer pushes values to the consumer whenever values are available. This approach is more flexible, because values can arrive synchronously or asynchronously.

- [Rxjava](https://github.com/ReactiveX/RxJava)

## Concepts covered

- Observables Overiew
	- Create and Just Factory
	- The Observer Interface
	- Shorthand Lambda Expressions
	- Cold vs Hot Observables
	- Connectable Observables
	- Range and Interval Factories
	- Future, Empty and Never Factories
	- Error Factory
	- Defer Factory
	- Single Factory
	- Maybe Factory
	- Completable Observable
	- Dispose using Disposable
	- Handling disposal in the Observer
	- Composite Disposable
