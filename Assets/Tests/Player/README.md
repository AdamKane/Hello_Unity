# Player Tests Documentation

This directory contains automated tests for player functionalities within the Hello_Unity project.

## Overview

The `PlayerTests.cs` file includes play mode tests designed to verify the correct behavior of player-related features. These tests are categorized into 'Fast' and 'Slow' to facilitate different testing pipelines and priorities.

Tests are written using the NUnit framework and Unity's testing tools, specifically leveraging the UnityTest attribute for coroutine-based test cases.

The 'Fast' category is intended for tests that run quickly and are used for frequent validation, while the 'Slow' category is reserved for more comprehensive tests that may take longer to execute.
