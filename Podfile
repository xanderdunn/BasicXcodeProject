platform :ios, '8.0'

target :BasicXcodeProject, :exclusive => true do
    # pod 'Reachability'              # test for an Internet connection
    # pod 'MagicalRecord'             # make Core Data much easier to use
    # pod 'MBProgressHUD'             # Progress indicator
    # pod 'HPGrowingTextView'         # text field that grows to fit the text contained in it
    # pod 'CrashlyticsFramework'      # Crash reporting
    # pod 'UICKeyChainStore'          # API Wrapper for Keychain Services
    # pod 'GoogleAnalytics-iOS-SDK'   # User statistics tracking
    # pod 'Parse-iOS-SDK'             # Cloud platform for sending user feedback
    # pod 'SDCAlertView'              # UIAlertView replacement so I can set the cancel button's tintColor
end

target :KIF, :exclusive => true do
     pod 'KIF'                   # Automated UI testing
end

# Every pod that should be listed in the Acknowledgements should be listed here
target :Licenses do
    pod 'KIF'
end

# Update the Acknowledgements.plist file on every pod update
post_install do | installer |
    require 'fileutils'
    FileUtils.cp_r('Pods/Pods-Licenses-acknowledgements.plist', 'BasicXcodeProject/SupportingFiles/Settings.bundle/Acknowledgements.plist', :remove_destination => true)
end

# Manually update for this project
# Toast: /local/dev/objc/memories/LearningApp/UI/Toast; git fetch upstream; git rebase upstrem/master; git push

# Useful pods to remember
# AFInformationView = pop-up bubbles with information
# TITokenField = a field that tokenizes names, like the To: field in the Mail app
# AQGridView =
# TISpringLoadedViews =
# TISwipeableTableView =
# 'CocoaLumberjack' = NSLog but better

# Core Data
# FRUniqueManagedObject         # Efficient find or create Core Data algorithm, no pod for this project
# pod 'KCOrderedAccessorFix'    # Fixes "CoreDataGeneratedAccessors" for ordered, to-many relationships

# Code Structure
# pod 'ReactiveCocoa'           # not currently used, testing

# View Controllers
# CRNavigationController = nice UINavigationController navigationBar blurring
# Tapkulibrary = many useful things including a calendar view

# General Views
# 'iOS-Blur' # iOS7-style blurring
# 'Shimmer' # A shimmer across a view as in the "Slide to unlock" text

# Pop-overs
# 'SMCalloutView' = a tip pop-over with an arrow like in the Apple Maps app
# 'WYPopoverController'
# FBTooltipView in FacebookSDK

# Notifications
# 'CRToast' = notifications at the top status bar
# pod 'TSMessages'                # display non-intrusive messages, I don't currently have an application for this
# 'TWMessageBarManager' # Very similar to the above two
# ClusterPrePermissions = proper way to ask users for permission to access things like contacts and photos

# Buttons
# pod 'BButton' = Nice buttons

# PDFs
# 'MOOMaskedIconView' = black and white vector masks to create icons
# 'UIImage+PDF' = Any PDF to UIImage

# Syntax Highlighting
# 'Fragaria' # OS X only

# Text
# 'HTAutocompleteTextField' =
# 'OHAttributedLabel' = UILabel that supports NSAttributedString
# CoreTextHyperlinkView = Make link text automatically tapable
# 'CHCSVParser' = CSV parsing

# High performance data structures
# 'PJTernarySearchTree' = best for text autocompletion
#

# Sharing
# 'ShareKit'

# Project Tools
# ImageOptim and ImageAlpha for compressing images in bundle
# Alcatraz = Xcode package manager
# mogenerator = Generate Core Data setters and getters
