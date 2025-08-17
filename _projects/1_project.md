---
layout: page
title: Calendly - Enterprise Calendar Application
subtitle: Java, SOLID Principles, Design Patterns, TDD, 98% Test Coverage
permalink: /projects/1_project/
thumbnail: assets/img/calendly.jpg
---

**Calendly** is an enterprise-level calendar application demonstrating advanced software engineering practices. Built with Java, it showcases SOLID principles, 6+ design patterns, MVC architecture, and comprehensive test-driven development.

## 🏗️ Architecture & Design

### Design Patterns Implemented
- **Command Pattern**: Encapsulates user actions as objects for flexible command execution
- **Factory Pattern**: Creates appropriate instances of models, views, and controllers
- **Adapter Pattern**: Bridges object-oriented operations to command-based execution
- **Builder Pattern**: Constructs complex calendar events and DTOs
- **Observer Pattern**: Provides controlled access to model data through read-only interfaces
- **Strategy Pattern**: Dynamically selects and executes commands based on user input

### MVC Architecture
- **Model Layer**: Core business logic with `ICalendarModel` interface
- **View Layer**: Multiple UI implementations (GUI, Interactive Console, Headless)
- **Controller Layer**: Command processing and user interaction coordination

## 🧪 Testing Excellence

### Test-Driven Development (TDD)
- **31 Test Classes** with extensive unit and integration tests
- **Test-to-Code Ratio**: ~60% (31 test files vs 52 source files)
- **Line Coverage**: **98%** - Near-perfect code coverage
- **Mutation Coverage**: **95%** - Excellent mutation testing results

### Testing Framework
- **JUnit 4.13.2** with advanced assertions and mocking
- **PIT Framework** for mutation testing
- **Automated testing** in Maven build pipeline

## 🚀 Key Features

- **Multi-Interface Support**: GUI, Interactive Console, and Headless modes
- **Event Management**: Create, edit, copy, and delete calendar events
- **Calendar Operations**: Multiple calendar support with timezone handling
- **Data Import/Export**: CSV file support for calendar data persistence
- **Command Processing**: Robust command parsing and execution system
- **Scalable Architecture**: Easy to extend with new commands and views

## 💻 Technical Stack

- **Language**: Java 11
- **Build Tool**: Maven 4.0.0
- **Testing**: JUnit 4.13.2, PIT Mutation Testing 1.17.2
- **Architecture**: MVC with SOLID Principles
- **Design Patterns**: 6+ patterns implemented
- **Code Quality**: 15,000+ lines with comprehensive documentation

## 🎯 Learning Outcomes

This project demonstrates:
- **Enterprise-level software engineering** practices
- **Clean code principles** and maintainable architecture
- **Comprehensive testing strategies** for production-ready code
- **Scalable design patterns** for extensible applications
- **Professional development workflow** with proper documentation

[View Project on GitHub](https://github.com/virtual457/Calendly){: .btn .btn-primary .btn-sm}
[View Documentation](https://github.com/virtual457/Calendly/blob/master/README.md){: .btn .btn-outline-primary .btn-sm}
