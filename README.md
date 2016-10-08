aospa_local_bacon
======================

Local Manifest for oneplus bacon devices

Getting Started
---------------

To get started with Android, you'll need to get
familiar with [Git and Repo](http://source.android.com/download/using-repo).

Make a build directory:

	mkdir Andoid (or whatever name you choose)
	cd Android (or the name  you chose)
	mkdir .repo/local_manifests

To initialize your local repository using the Cyanogemod manifest, use commands like these:

    repo init -u https://github.com/AOSPA/manifest -b marshmallow-caf

    curl -L -o .repo/local_manifests/bacon.xml -O -L https://raw.github.com/ZeroJim/aospa_local_bacon/mm-caf/bacon.xml
 
    	( or Download: https://github.com/ZeroJim/aospa_local_bacon/mm-caf/bacon.xml)
		and place it in ~/Android/.repo/local_manifest.xml (or ~/'name you chose'/.repo)

Then to sync up:

    repo sync
