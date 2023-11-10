swak4Foam installation

1- create working directory 

mkdir -p $FOAM_RUN

2- go to working directory

cd "$HOME/OpenFOAM/$USER-$WM_PROJECT_VERSION"

copy and unpack at the zip file there.

3-run the following commands:
./maintainanceScripts/compileRequirements.sh
./AllwmakeAll
