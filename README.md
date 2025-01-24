# Queue Library

A C# DLL library that implements a generic `Queue` class named `Q`. This library provides a variety of methods to efficiently manage queues, including operations like enqueueing, dequeueing, inserting, removing, and copying items.

## Features

- **Enqueue**: Adds an item to the end of the queue.
- **Dequeue**: Removes and returns the item at the front of the queue.
- **Peek**: Views the item at the front of the queue without removing it.
- **Head**: An alias for `Peek`, used to retrieve the first item.
- **Insert**: Adds an item to the end of the queue (same as `Enqueue`).
- **Remove**: Removes and returns the item at the front of the queue (same as `Dequeue`).
- **Copy**: Copies items from one queue to another.
- **CopyWithProtection**: Creates a new queue by copying items from the original queue while protecting the first item.

## Getting Started

Follow the steps below to set up and use the library.

### Prerequisites

Make sure you have the following installed on your machine:

- [.NET Framework](https://dotnet.microsoft.com/download/dotnet-framework) or [.NET Core](https://dotnet.microsoft.com/download/dotnet)  
- A C# development environment (e.g., [Visual Studio](https://visualstudio.microsoft.com/), [Rider](https://www.jetbrains.com/rider/), or [Visual Studio Code](https://code.visualstudio.com/))  

### Installation

1. **Clone the repository**:  
   Clone the repository to your local machine using the following command:  
   ```bash
   git clone https://github.com/Adanz22/Queue.git
