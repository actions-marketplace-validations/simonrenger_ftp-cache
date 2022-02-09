# Simple FTP Cache Action

Allows you to treat a FTP Server as caching server.

## Inputs

```yml
  host:
    description: 'Host'
    required: true
  upload:
    description: 'Upload or Download'
    default: true
    required: true
  user:
    description: 'User'
    required: true
  password:
    description: 'Password'
    required: true
  source:
    description: 'Source Folder'
    required: true
  destination:
    description: 'Destination Folder'
    required: true
  secure:
    description: 'Secure'
    required: false
    default: false
  timeout:
    description: 'timeout'
    required: false
    default: 30000
  archive-name:
    description: 'Cache Name. By default its the name of the os runner and cache'
    required: false
  archive:
    description: 'Creates a tar archive for the given folder and uploads/downloads that'
    required: false
    default: true
````
