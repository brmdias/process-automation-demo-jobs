# Job definition
Job definition is available [here](Export_ROI_metrics_to_CSV.yaml)

# Job options
**PAOP Host IP**: IP Address/Hostname for the PAoP hosting the ROI Metrics.
**API Version**: API Version of the PAoP server. You can get it from the System Report page.
**API Token**: you're API token. This needs to be saved on PAoP on Key Storage. Here are the instructions to create an API token for your user: [New User Token Creation](https://docs.rundeck.com/docs/api/api_basics.html#running-the-welcome-project-and-new-user-token-creation)
**CSV File Path**: Destination for the CSV file generated from the job. Needs to be full file path, including file name.

# Example
Example job with ROI data:
<img width="1263" alt="Pasted image 20230914152650" src="https://github.com/brmdias/process-automation-demo-jobs/assets/100204121/727addcf-4805-4cc5-b92e-de01f92a59ae">

Example from CSV file generated from this job:
<img width="867" alt="Pasted image 20230914153015" src="https://github.com/brmdias/process-automation-demo-jobs/assets/100204121/28a712f2-989d-45e7-8f0d-8332ee92595f">
