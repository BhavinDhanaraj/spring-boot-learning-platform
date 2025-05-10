---
layout: default
title: Java Basics Review
---

# Java Basics Review

## Learning Objectives
- Refresh core Java programming concepts
- Understand object-oriented principles in Java
- Master collections, generics, and functional features
- Build a simple command-line application

## Introduction

Spring Boot is built on Java, so a solid understanding of Java fundamentals is essential. This lesson refreshes key concepts you'll need throughout your Spring Boot journey.

## Object-Oriented Programming in Java

Java is primarily an object-oriented language built around classes and objects. Let's review the core principles:

### Classes and Objects

A class is a blueprint for creating objects:

```java
public class Person {
    // Fields (attributes)
    private String name;
    private int age;
    
    // Constructor
    public Person(String name, int age) {
        this.name = name;
        this.age = age;
    }
    
    // Methods
    public String getName() {
        return name;
    }
    
    public void setName(String name) {
        this.name = name;
    }
    
    public int getAge() {
        return age;
    }
    
    public void setAge(int age) {
        this.age = age;
    }
    
    public void greet() {
        System.out.println("Hello, my name is " + name);
    }
}