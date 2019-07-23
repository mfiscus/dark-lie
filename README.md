# dark-lie

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

1. Check out a clone of this repo to your local bin directory
   ```bash
   git clone https://github.com/mfiscus/dark-lie.git ~/bin
   ```
2. Run `~/bin/dark-lie`

## Optional

1. Add dark-lie to your `.bash_profile`
   ```bash
   export PATH=${HOME}"/bin:"${PATH}
   export weather=$( dark-lie )
   echo ${weather}
   ```