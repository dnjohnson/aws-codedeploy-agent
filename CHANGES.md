# 0.0.2

* Fix hanging deployment issue, where the server responds to a command
  acknowledgement with 'Succeeded' or 'Failed' command status, by sending an
  update back to the server to echo the command status and continue/unstick
  the deployment. (panthomakos)

# 0.0.1

* Converted to a gem for easier installation and use. (panthomakos)
