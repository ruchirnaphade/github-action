- 3 Blocks
	- Workflows:
		attached to repo, as many as you want, 
		includes one or mode jobs
		Workflows triggers upon event
	- Jobs:
		Define a runner (execution environment)
		contains one or more steps
		can run in parallel or in sequential order
		can be conditional
	- Steps:
		Actual work is done in steps
		can execute a shell script or an action (predefined scripts by GitHub)
		Also can use custom or third party actions
		execute in order and can be conditional