# DatabricksJobExecution

Simple method to orchestrate job execution inside a Databricks environment

Notebooks:
- executeJob : Python notebook to interact, monitor and control job execution throught the Databricks API
- util : library notebook being used by other notebooks
- dummyNB : A simple notebook just for test purposes


Jobs Folder:
- Main_dummy_job.json : an example job able to orchestrate other jobs execution
- dummy_job_01...05.json: jobs being executed by the orchestrator job

If you want to use these jobs please replace the key values by your Databricks environment values
