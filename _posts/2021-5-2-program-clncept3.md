---
title: Program concept(part 3)
layout: post
---

## 1. Windows of S1. Main Section 
### 1. Start page
#### Destination:  
Like Start page on Eclipse, NetBeans or other programs.
#### Window properties:  
- PROP_CLOSING_DISABLED - false
- PROP_DRAGGING_DISABLED - true
- PROP_MAXIMIZATION_DISABLED - true
- PROP_SLIDING_DISABLED - true  
- PROP_UNDOCKING_DISABLED - true

### 2. Active map editor
#### Destination:  
The main program window where the user among others can view the content of the active map, edit layers, take measurements and add layers using the D'n'D mechanism.
#### Window properties:  
- PROP_CLOSING_DISABLED - true
- PROP_DRAGGING_DISABLED - true
- PROP_MAXIMIZATION_DISABLED - false
- PROP_SLIDING_DISABLED - true  
- PROP_UNDOCKING_DISABLED - true

### 3. MapDisplayer
#### Destination:  
Window, where user van view content of the map other than active, take measurements, się tools(can't edit Layers).
#### Window properties:  
 - PROP_CLOSING_DISABLED - false
- PROP_DRAGGING_DISABLED - false
- PROP_MAXIMIZATION_DISABLED - true
- PROP_SLIDING_DISABLED - false  
- PROP_UNDOCKING_DISABLED - false

### 4. PrintOut
#### Destination:  
Like PrintOut window on QGIS.
#### Window properties:  
 - PROP_CLOSING_DISABLED - false
- PROP_DRAGGING_DISABLED - true
- PROP_MAXIMIZATION_DISABLED - true
- PROP_SLIDING_DISABLED - true  
- PROP_UNDOCKING_DISABLED - false

## 2. Windows of S2. Project 
### 1. Project list
#### Destination:  
List of projects registered in the program in the form of a tree, where maps and printouts assigned to the project are displayed.
#### Window properties:  
- PROP_CLOSING_DISABLED - false
- PROP_DRAGGING_DISABLED - false
- PROP_MAXIMIZATION_DISABLED - true
- PROP_SLIDING_DISABLED - false  
- PROP_UNDOCKING_DISABLED - false

### 2. Noactive map layers
#### Destination:  
Window with the list of layers of inactive map - it is used mainly for copying layers to the active map.
#### Window properties:  
- PROP_CLOSING_DISABLED - false
- PROP_DRAGGING_DISABLED - false
- PROP_MAXIMIZATION_DISABLED - true
- PROP_SLIDING_DISABLED - false  
- PROP_UNDOCKING_DISABLED - false

## 3. Windows of S3. Layer Section 
### 1. Layers list
#### Destination:  
List od Layers(structure of map).
#### Window properties:  
- PROP_CLOSING_DISABLED - true
- PROP_DRAGGING_DISABLED - false
- PROP_MAXIMIZATION_DISABLED - true
- PROP_SLIDING_DISABLED - false  
- PROP_UNDOCKING_DISABLED - false

### 2. Selected items
#### Destination:  
Lis Layers with selected items.
#### Window properties:  
- PROP_CLOSING_DISABLED - false
- PROP_DRAGGING_DISABLED - false
- PROP_MAXIMIZATION_DISABLED - true
- PROP_SLIDING_DISABLED - false  
- PROP_UNDOCKING_DISABLED - false

## Window properties for all others:  
- PROP_CLOSING_DISABLED - false
- PROP_DRAGGING_DISABLED - false
- PROP_MAXIMIZATION_DISABLED - false
- PROP_SLIDING_DISABLED - false  
- PROP_UNDOCKING_DISABLED - false

## 4. Windows of S4. Tool Section
- Tool windows



## 5. Windows of S5. Properties Section.  
- Bookmarks
- Properties

## 6. Windows of S6. Table Section
- Tables
- Output

