# Architecture

The ESP32 Family Panel uses a modular application architecture.

## Design Goals

- Each application is independent
- Shared services handle common functions
- Hardware-specific code is isolated
- Additional displays can be supported later


## High Level Architecture


Applications

      |

Core Framework

      |

Services

      |

Hardware


## Applications

Examples:

- Chore Tracker
- Weather
- Flight Tracker


## Services

Examples:

- Display Service
- Storage Service
- Network Service
- Time Service
