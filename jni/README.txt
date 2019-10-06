Build with latest NDK

sdkmanager 'ndk-bundle'

export NDK=$ANDROID_HOME/ndk-bundle
export ANDROID_NDK=$NDK
export ANDROID_NDK_HOME=$NDK
export PATH=$NDK:$PATH
