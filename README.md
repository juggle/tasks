# WIP: Tasks
Async utility for executing tasks at specific points during a frame, or, at a point in time.

IE10/11+

## MicroTask
Shedules a MiroTask. Run synchronously after the main thread has run and imidiately before the next asynchronous task.

## RenderTask
Shedules a task to be run inside of an animation frame.

## PostRenderTask
Schedules a task to be run after paint, but, before the next frame.

## ScheduledTask
Schedules a task to be run at a specific time. Can specify date or delay.

## IntervalTask
Shedules an infinite running task, to be run every _n_ milliseconds.
