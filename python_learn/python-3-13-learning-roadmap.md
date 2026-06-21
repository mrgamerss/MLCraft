# Python 3.13.12 — Complete Learning Roadmap {Works all round!!}

## Phase 1 — Python Fundamentals (Weeks 1-2)

**1.1 Basic Syntax & Setup**
- Practice printing output and writing comments/docstrings for documentation
- Learn the core data types: strings, floats, booleans, lists, tuples, dictionaries, sets
- Get comfortable declaring and naming variables

**1.2 Control Flow**
- Learn if / elif / else branching
- Practice `for` loops (including `range`) and `while` loops
- Understand the less-common `for...else` / `while...else` construct

**1.3 Functions**
- Write basic functions with type-hinted parameters and return values
- Learn default arguments
- Learn `*args` and `**kwargs` for flexible function signatures
- Practice writing simple lambda functions

## Phase 2 — Data Structures & Collections (Weeks 3-4)

**2.1 Advanced Lists & Tuples**
- Learn list comprehensions, including nested and conditional ones
- Practice core list methods: append, extend, insert, pop, remove
- Learn tuple unpacking, including starred (`*rest`) unpacking

**2.2 Dictionaries & Sets**
- Learn dictionary comprehensions
- Practice merging dictionaries
- Learn set operations: union, intersection, difference, symmetric difference

**2.3 Iterators & Generators**
- Learn generator functions using `yield`
- Practice generator expressions
- Build a custom iterator class implementing `__iter__` and `__next__`

## Phase 3 — Object-Oriented Programming (Weeks 5-6)

**3.1 Classes & Objects**
- Learn class vs instance variables
- Practice `__init__`, instance methods, and naming conventions for "private" attributes
- Learn `@classmethod` and alternate constructors
- Learn `@staticmethod`
- Learn the `@property` decorator and its setter
- Practice inheritance and method overriding

**3.2 Magic Methods (Dunder Methods)**
- Learn `__str__` and `__repr__` for object representation
- Learn `__add__` for operator overloading
- Learn `__eq__` for custom equality
- Learn `__len__` and `__call__` for making objects sized/callable

## Phase 4 — File I/O & Exception Handling (Weeks 7-8)

**4.1 File Operations**
- Practice reading and writing files using `with open(...)`
- Learn to work with JSON (`dumps` / `loads`)
- Learn to read and write CSV files

**4.2 Exception Handling**
- Learn try / except / else / finally blocks
- Practice catching specific and multiple exception types
- Learn to define and raise custom exception classes
- Learn how to write a context manager using `@contextmanager`

## Phase 5 — Modules & Packages (Weeks 9-10)

**5.1 Working with Modules**
- Learn to create your own module and import it (plain import, `from ... import`, aliasing)
- Understand why `from module import *` is discouraged
- Learn the `if __name__ == "__main__":` guard

**5.2 Package Structure**
- Learn how a package is organized: `__init__.py`, modules, and subpackages
- Understand how Python resolves imports within a package

## Phase 6 — Advanced Features (Weeks 11-12)

**6.1 Decorators**
- Learn how to write a basic decorator (e.g., a timing decorator)
- Learn how to write a decorator that itself takes arguments

**6.2 Advanced Python 3.13 Features**
- Learn the f-string debugging shorthand (`{value = }`)
- Learn type hints using `List`, `Dict`, `Optional`, `Union`, `Any`
- Learn generic functions with `TypeVar`

**6.3 Context Managers & Async**
- Learn `async`/`await` syntax and `asyncio.run`
- Practice writing and awaiting async functions
- Learn async context managers (e.g., async file handling)

## Phase 7 — Best Practices & Tools (Weeks 13-14)

**7.1 Testing**
- Learn `unittest`-style tests (test classes, assertions)
- Learn `pytest`-style tests (plain `assert` functions)
- Learn the basics of mocking with `unittest.mock`

**7.2 Package Management**
- Learn core `pip` commands: install, install from `requirements.txt`, freeze
- Learn how to create and activate virtual environments (Linux/Mac and Windows)
- Know how to upgrade pip itself

**7.3 Code Quality**
- Learn the role of type checkers (e.g., mypy)
- Learn the role of linters (e.g., pylint, flake8)
- Learn the role of formatters (e.g., black, isort)
- Practice writing well-typed utility functions with optional parameters

## Phase 8 — Real-World Applications (Weeks 15-16)

**8.1 Web Development (Flask)**
- Learn to set up a minimal Flask app
- Learn basic routing, including routes with URL parameters
- Learn to render templates and run the app in debug mode

**8.2 Data Science (Basic)**
- Practice working with lists of dictionaries as simple datasets
- Learn to compute aggregates (sum, average) using built-ins
- Learn to find max/min and sort data using a `key` function

**8.3 Performance Optimization**
- Learn caching with `functools.lru_cache`
- Understand why list comprehensions tend to outperform manual loops
- Learn the basics of profiling code with `cProfile`

## Quick Reference: Python 3.13 Highlights

**New in Python 3.13**
- Enhanced error messages with better suggestions
- Improved type narrowing in type checkers
- Better performance for certain operations
- New typing features for more precise type hints

**Common Built-in Functions to Know**
- `len`, `type`, `print`, `input`, `int`, `float`, `str`
- `list`, `dict`, `set`, `tuple`, `range`, `enumerate`
- `zip`, `map`, `filter`, `sorted`, `sum`, `min`, `max`
- `any`, `all`, `isinstance`, `hasattr`, `getattr`

**Common Standard Library Modules**
- `os`, `sys`, `datetime`, `math`, `random`
- `json`, `csv`, `re`, `subprocess`, `collections`
- `itertools`, `functools`, `typing`, `logging`
- `unittest`, `asyncio`, `threading`, `multiprocessing`

## Learning Path Summary

| Weeks | Focus |
|---|---|
| 1-2 | Fundamentals (syntax, control flow, functions) |
| 3-4 | Data structures (lists, dicts, sets, generators) |
| 5-6 | OOP (classes, inheritance, magic methods) |
| 7-8 | I/O & exceptions (files, JSON, error handling) |
| 9-10 | Modules & packages (imports, packaging) |
| 11-12 | Advanced features (decorators, async, typing) |
| 13-14 | Best practices (testing, quality, tools) |
| 15-16 | Real-world applications (web, data, optimization) |

## Practice Projects

- [ ] CLI calculator
- [ ] Todo list manager
- [ ] File organizer
- [ ] Simple web scraper
- [ ] REST API with Flask
- [ ] Data analysis tool
- [ ] Chat application
- [ ] Task scheduler

> Practice regularly, read documentation, and build projects.
