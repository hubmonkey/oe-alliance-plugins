ACLOCAL_AMFLAGS = -I m4

SUBDIRS = AutoBouquetsMaker DLNABrowser DLNAServer StreamTV 3GModemManager WebBrowser OpenUitzendingGemist TunerServer OnDemand Fempa LCD4linux

if AZBOX
SUBDIRS += Blindscan
endif

if VUPLUS
SUBDIRS += VuplusEvent HbbTV
endif

if XTREND
SUBDIRS += XtrendFancontrol Blindscan XtrendRemote
endif

if ODIN
SUBDIRS += XtrendFancontrol Blindscan
endif

if ODINM7
SUBDIRS += OdinM7VFDControl
endif

if VENTON
SUBDIRS += VentonFancontrol Blindscan MICOMUpgrade HbbTV
endif

if INI
SUBDIRS += VentonFancontrol Blindscan MICOMUpgrade HbbTV
endif

if INIHDP
SUBDIRS += TransCodingSetup
endif

if VUUNO
SUBDIRS += FirmwareUpgrade Blindscan VuRemote
endif

if VUULTIMO
SUBDIRS += FirmwareUpgrade Blindscan VuRemote
endif

if VUDUO
SUBDIRS += VuDuoFanControl
endif

if VUSOLO2
SUBDIRS += FirmwareUpgrade VuRemote TransCodingSetup Blindscan
endif

if VUDUO2
SUBDIRS += FirmwareUpgrade VuRemote TransCodingSetup Blindscan
endif

if GIGABLUE
SUBDIRS += GigaBlueVFDControl Blindscan
endif

if XP1000
SUBDIRS += XtrendRemote SF8VFDControl
endif

if HAVE_TEMPFANCONTROL
SUBDIRS += TempFanControl
endif
