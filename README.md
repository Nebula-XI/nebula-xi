# Nebula-XI Super Project

## Requirements

CMake 3.21, Ninja 1.10.2, Boost 1.75, GCC 10.3

## Configuring

### Linux x86_64

`cmake --preset linux-x64-release`

`cmake --preset linux-x64-debug`

## Building

### Linux x86_64


`cmake --build --preset linux-x64-release`

`cmake --build --preset linux-x64-release-rebuild`

`cmake --build --preset linux-x64-release-verbose`

`cmake --build --preset linux-x64-debug`

`cmake --build --preset linux-x64-debug-rebuild`

`cmake --build --preset linux-x64-debug-verbose`

## Testing

### Linux x86_64


`ctest --preset linux-x64-release`

`ctest --preset linux-x64-debug`



## Documentation

### 1. Units Tree Configuration (UTC)

### 1.1. Description

### 1.2. Basic syntax

### 1.3. Parsing

### 1.4. Example

### 2. Units Information Structures (UIS)

### 2.1. Description

### 2.2. Example

### 3. AXI Drivers (AD)

### 3.1. Description

### 4. Units Device Classes (UDC)

### 4.1. Description

### 5. Components Library (CL)

### 6. Carrier Boards (CB)

### 6.1. Carrier Boards Library (CBL)

### 6.1.1. Carrier Boards Interface (CBI)

### 6.1.2. Carrier Boards Subsystems (CBS)

### 6.1.3. Carrier Boards Creator (CBC)

### 7. Mezzanine Modules (MM)

### 7.1. Mezzanine Modules Library (MML)

### 7.1.1. Mezzanine Modules Interface (MMI)

### 7.1.2. Mezzanine Modules Subsystems (MMS)

### 7.1.3. Mezzanine Modules Creator (MMC)

### 8. Boards Resource Manager (BRM)

### 9. Hardware Abstraction Layer (HAL)
