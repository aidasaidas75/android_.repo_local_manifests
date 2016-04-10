CM12.1 Manifests
========================

Local manifests to build Android LolliPop 5.1 to E610

To initialize CM12.1 Repo:

    repo init -u git://github.com/CyanogenMod/android.git -b cm-12.1 -g all,-notdefault,-darwin

To initialize Repo's:

    curl --create-dirs -L -o .repo/local_manifests/local_manifest.xml -O -L https://raw.githubusercontent.com/aidasaidas75/android_.repo_local_manifests/cm-12.1/local_manifest.xml

To sync:

    repo sync

To apply patchs:

    sh device/lge/msm7x27a-common/patches/apply.sh

To initialize the environment

    . build/envsetup.sh
