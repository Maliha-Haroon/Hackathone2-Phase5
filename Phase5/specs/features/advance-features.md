# Advanced Features Spec

## Recurring Tasks
- Auto-create next task after completion
- Publish "task-completed" event to Kafka topic "task-events"

## Due Dates & Reminders
- Store due date in task object
- Publish reminder events to Kafka topic "reminders"
- Dapr Jobs API triggers reminder service

## Intermediate Features
- Priorities, Tags, Search, Filter, Sort
- Event-driven design: publish all changes to "task-events"

## Real-Time Sync
- Any client updates task → publish to "task-updates" → WebSocket service broadcasts to all clients
