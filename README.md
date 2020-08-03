\# Roomservice for hi6250 devices (LineageOS 15.1)
This File adds the device-specific Repositorys to build LineageOS 15.1

## How to use?
1. Open a Terminal and open your build directory, example:
`cd build/lineage-15.1`

2. Enter .repo/local_manifests directory and download the roomservice file:
`cd .repo/local_manifests/ && wget -O roomservice.xml https://raw.githubusercontent.com/su3817806/lineage_hi6250/lineage-15.1/roomservice.xml`

3. Go back to your build directory and download the repositorys:
`cd ../../ && repo sync`

Done! Now you can start building LineageOS for your hi6250 device :)
