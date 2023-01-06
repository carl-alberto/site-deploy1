initialization
	  
	  
Secret variables that you need to configure :


PANTHEONSITEUUID: "${{ secrets.PANTHEONSITEUUID }}"

PANTHEONEMAIL: "${{ secrets.PANTHEONEMAIL }}"

https://pantheon.io/docs/machine-tokens/

MACHINETOKEN: "${{ secrets.MACHINETOKEN }}"

https://pantheon.io/docs/ssh-keys

private key in gh

STAGING_PRIVATE_KEY: "${{ secrets.STAGING_PRIVATE_KEY }}"

add pub in pantheon


GH_REF2: "${{ github.ref }}'

recommended wp folder structure