# Industrial Biogas Plant Automation and Safety Control System

A robust, microcontroller-free automation and safety control system designed for harsh industrial environments, implementing complete biogas production cycle management with fail-safe protocols.

> **⚠️ Note on Project Visibility**
> 
> This project is currently deployed as a live, fully operational system running daily automation. Due to ongoing patent proceedings by the institution and copyright protections on the circuit design and technology, certain implementation details, schematics, and proprietary components cannot be publicly disclosed on this repository.

## 🚀 Overview

This project implements a fully automated control system for industrial biogas plants using industrial relay logic instead of microcontrollers, ensuring reliable operation in corrosive and challenging atmospheric conditions. The system manages the entire biogas production cycle from dome filling to storage, with integrated multi-layer safety protocols to prevent hazardous situations.

## ⚙️ System Architecture

### Phase 1: Production Automation
- **Dome Level Detection**: Automatic sensing of biogas dome capacity
- **Sequential Control**: Triggers compressor and Scheruber filtration system upon dome fill-up
- **Gas Transfer**: Automated solenoid valve control for safe gas transfer to storage tanks

### Phase 2: Safety Management System
- **Three-Light Visual Alert**: Green/Amber/Red indicator system in mess hall
- **Audible Alarm Integration**: Multi-location alarm bells for emergency notifications
- **Hardware Interlocks**: Safety switches that require manual engagement during alerts
- **Pressure Monitoring**: Real-time storage tank pressure tracking with automatic shutdown

## 🛡️ Key Safety Features

- **Fail-Safe Design**: Production circuit automatically locks during safety alerts
- **Manual Override Requirement**: Safety switch must be engaged for gas usage during red alerts
- **Multi-point Alarm System**: Visual and audible alerts across three locations
- **Pressure-based Shutdown**: Automatic system halt during over-pressurization conditions

## 🔧 Hardware Components

- **Control System**: Industrial Relay Modules (Timer Relays, High-Ampere Relays)
- **Actuators**: Solenoid Valves, Compressor Units, Scheruber Filtration System
- **Sensors**: Pressure Switches, Level Sensors
- **Power Management**: AC/DC Converters, Industrial Power Supplies
- **Interface**: Three-Light Indicator System, Alarm Bells, Safety Switches

## 🎯 Technical Highlights

- **Environment Resilience**: Microcontroller-free design for harsh conditions
- **Hardware Reliability**: Industrial-grade components for continuous operation
- **Safety-Centric Architecture**: Multiple redundant safety layers
- **Real-time Monitoring**: Continuous pressure and level monitoring
- **User-friendly Interface**: Simple visual indicators for non-technical operators

## 📊 System Workflow

1. **Normal Operation**: Green light indicates safe gas usage from storage tank
2. **Warning State**: Amber light signals approaching capacity limits
3. **Critical State**: Red light with alarms activates safety protocols
4. **Emergency Lock**: Production circuit disabled until manual reset

## 🔒 Intellectual Property Status

- **Patent Pending**: Circuit design and automation technology submitted for institutional patent
- **Live Deployment**: Fully operational system running daily automated cycles
- **Limited Disclosure**: Public repository contains conceptual overview only
- **Proprietary Technology**: Detailed schematics and implementation specifics protected under copyright

## 💡 Innovation

This project demonstrates how complex industrial automation can be achieved without microcontrollers, providing extreme reliability in environments where electronic components would fail. The hardware-based interlock system ensures operational safety even in worst-case scenarios.

## 🛠️ Tools & Technologies

- Industrial Relay Logic
- Timer Relay Modules
- Solenoid Valves
- Pressure Switches
- AC/DC Power Converters
- Industrial Control Wiring

## 📁 Project Structure
