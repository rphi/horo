complications
=============

A "complication" in Horo is a plug-in to the "caliber" or core mechanism that runs tasks
within a specific environment.

The basic tasks a complication must perform are the following:
 - Subscribe to a RabbitMQ/Celery message queue
 - Consume messages (containing tasks) from the queue
 - Pull the task resource bundle from the caliber API (this contains any source or
   other assets required for the task to execute)
 - Execute the task
 - Publish the results, telemetry and any output assets back to the caliber API
