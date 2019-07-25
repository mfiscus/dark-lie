# dark-lie

## Build status
[![CircleCI](https://circleci.com/gh/mfiscus/dark-lie.svg?style=svg)](https://circleci.com/gh/mfiscus/dark-lie)

## Prerequisites

1. Go to https://ipinfo.io/developers
*   Sign up for a free developer account
*   Create a file named dark-lie_ip.token and put your key in it
      ```bash
      echo "<your key here>" > ~/bin/dark-lie_ip.token
      ```

2. Go to https://darksky.net/dev/register
*    Sign up for a free developer account
*    Create a file named dark-lie_ds.token and put your key in it
       ```bash
        echo "<your key here>" > ~/bin/dark-lie_ds.token
       ```

## Installation

1. Download dark-lie to your local bin directory
   ```bash
   cd ~/bin && wget https://raw.githubusercontent.com/mfiscus/dark-lie/master/dark-lie
   ```
2. Make script executable
   ```bash
   chmod +x dark-lie
   ```

3. Run `./dark-lie`

## Optional

1. Add dark-lie to your `.bash_profile`
   ```bash
   export PATH=${HOME}"/bin:"${PATH}
   export weather=$( dark-lie )
   echo ${weather}
   ```
