# Task Context Repository

This repository contains task context and state information managed by the Task Context Manager.

## Structure

- `tasks.json` - Task definitions and metadata
- `current_task.json` - Current active task reference
- `context.json` - Task context and conversation history
- `compressed_context.json` - Compressed context for token management

## Usage

This repository is managed automatically by the Task Context Manager MCP server.
Each task state change is committed to maintain a complete history.
