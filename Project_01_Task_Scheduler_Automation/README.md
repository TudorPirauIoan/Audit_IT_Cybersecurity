# Automation and Logging with Windows Task Scheduler

This project demonstrates the execution of scheduled batch jobs within a Windows environment, illustrating core concepts of system maintenance and logging mechanisms.

## Objective

To create and schedule a batch script (`.bat`) using Windows Task Scheduler for recurring, unattended execution, generating an activity log with accurate system timestamps.

## Project Components

1. **`script_test.bat`**: A script that retrieves the current system date and time, appending the record to a text file to maintain an activity log.
2. **Task Scheduler Configuration**:
   * **Trigger**: Scheduled for daily execution or run on-demand.
   * **Action**: Background execution of the batch script.

## IT Audit Perspective

Understanding the Task Scheduler utility supports IT Audit and security assessments by:
* Enabling the verification of automated jobs that handle critical operations, such as data backups and file transfers.
* Facilitating the evaluation of how an operating system manages and logs automated events.
* Providing a basis for traceability, where the resulting log files serve as technical evidence of execution status and timing.
