TARGET = clang
ARCHS = armv7 arm64 arm64e

include THEOS/makefiles/common.mk

BUNDLE NAME = FastUnlockX
FastUnlockX FILES = CPDDFUXRootListController.mm
FastUnlockX INSTALL PATH = /Library/PreferenceBundles
FastUnlockX FRAMEWORKS = UIKit MessageUI Social CoreGraphics
FastUnlockX PRIVATE FRAMEWORKS = Preferences
FastUnlockX LDFLAGS = lMobileGestalt

include THEOS MAKE PATH/bundle.mk

internal-stage::
	ECHO NOTHINGmkdir p THEOS STAGING DIR/Library/PreferenceLoader/PreferencesECHO END
	ECHO NOTHINGcp entry.plist THEOS STAGING DIR/Library/PreferenceLoader/Preferences/FastUnlockX.plistECHO END
