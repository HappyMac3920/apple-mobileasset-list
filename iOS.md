# Audiences

`01c1d682-6e8f-4908-b724-5501fe3f5e5c`  software updates <br>
`c724cb61-e974-42d3-a911-ffd4dce11eda`  security updates <br>
`0c88076f-c292-4dad-95e7-304db9d29d34`  other MobileAssets <br>


# Software update assets

These can be accessed using the software updates audience. <br>

#### com.apple.MobileAsset.SoftwareUpdate
Usage: The OTA software updates are fetched from here. <br>
Availability: hybrid (both mesu and pallas) <br>
mesu.apple.com link: `https://mesu.apple.com/assets/com_apple_MobileAsset_SoftwareUpdate/com_apple_MobileAsset_SoftwareUpdate.xml` <br>
Pallas example curl command:
`curl -H 'Content-Type: application/json' -H 'Accept: application/json' https://gdmf.apple.com/v2/assets --data '{"AssetAudience":"01c1d682-6e8f-4908-b724-5501fe3f5e5c","HWModelStr":"D74AP","ProductType":"iPhone15,3","CertIssuanceDay":"2020-09-29","ClientVersion":2,"AssetType":"com.apple.MobileAsset.SoftwareUpdate","ProductVersion":"15.0","BuildVersion":"19A346"}'` <br>
#### com.apple.MobileAsset.SplatSoftwareUpdate
Usage: The Rapid Security Response is fetched from here. <br>
Availability: pallas only <br>
Pallas example curl command:
`curl -H 'Content-Type: application/json' -H 'Accept: application/json' https://gdmf.apple.com/v2/assets --data '{"AssetAudience":"01c1d682-6e8f-4908-b724-5501fe3f5e5c","CertIssuanceDay":"2020-09-29","ClientVersion":2,"AssetType":"com.apple.MobileAsset.SplatSoftwareUpdate","CompatibilityVersion":20,"RestoreVersion":"20.1.371.0.0,0","Build":"20A371","HWModelStr":"D99AP"}'` <br>
For now this command will give you an empty response but in the future it might include data when the first public RSR is released.
#### com.apple.MobileAsset.SoftwareUpdateDocumentation
Usage: The OTA's documentation (what's new in the update) is fetched from here. <br>
Availability: hybrid (both mesu and pallas) <br>
mesu.apple.com link: `https://mesu.apple.com/assets/com_apple_MobileAsset_SoftwareUpdateDocumentation/com_apple_MobileAsset_SoftwareUpdateDocumentation.xml` <br>
Pallas example curl command:
`curl -H 'Content-Type: application/json' -H 'Accept: application/json' https://gdmf.apple.com/v2/assets --data '{"AssetAudience":"01c1d682-6e8f-4908-b724-5501fe3f5e5c","CertIssuanceDay":"2020-09-29","ClientVersion":2,"AssetType":"com.apple.MobileAsset.SoftwareUpdateDocumentation","SUDocumentationID":"iOS1641Long","DeviceName":"iPhone"}'` <br>
#### com.apple.MobileAsset.MobileSoftwareUpdate.UpdateBrain
Usage: The OTA's update controller is fetched from here. <br>
Availability: hybrid (both mesu and pallas) <br>
mesu.apple.com link: `https://mesu.apple.com/assets/com_apple_MobileAsset_MobileSoftwareUpdate_UpdateBrain/com_apple_MobileAsset_MobileSoftwareUpdate_UpdateBrain.xml` <br>
Pallas example curl command:
`curl -H 'Content-Type: application/json' -H 'Accept: application/json' https://gdmf.apple.com/v2/assets --data '{"AssetAudience":"01c1d682-6e8f-4908-b724-5501fe3f5e5c","CertIssuanceDay":"2019-09-06","ClientVersion":2,"AssetType":"com.apple.MobileAsset.MobileSoftwareUpdate.UpdateBrain","CompatibilityVersion":20}'` <br>

# Other assets

These can be accessed using the other MobileAssets audience. <br>
#### com.apple.MobileAsset.Activity.Achievements
Usage: The achievement assets used in the Fitness app if you get an achievement. <br>
Availability: mesu only <br>
mesu.apple.com link: `https://mesu.apple.com/assets/com_apple_MobileAsset_Activity_Achievements/com_apple_MobileAsset_Activity_Achievements.xml` <br>
#### com.apple.MobileAsset.ActivityChallengeAssets
Usage: The achievement assets used in the Fitness app if you get an achievement. <br>
Availability: Pallas only <br>
WARNING: the response will be large! <br>
Pallas example curl command:
`curl -H 'Content-Type: application/json' -H 'Accept: application/json' https://gdmf.apple.com/v2/assets --data '{"AssetAudience":"0c88076f-c292-4dad-95e7-304db9d29d34","AssetType":"com.apple.MobileAsset.ActivityChallengeAssets","ClientVersion":2}'` <br>
#### com.apple.MobileAsset.AppletTranslationLibraryAssets
Usage: Unknown. <br>
Availability: mesu only <br>
mesu.apple.com link: `https://mesu.apple.com/assets/com_apple_MobileAsset_AppletTranslationLibraryAssets/com_apple_MobileAsset_AppletTranslationLibraryAssets.xml` <br>
#### com.apple.MobileAsset.AudiogramAssets
Usage: Audiogram feature. <br>
Availability: mesu only <br>
mesu.apple.com link: `https://mesu.apple.com/assets/com_apple_MobileAsset_AudiogramAssets/com_apple_MobileAsset_AudiogramAssets.xml` <br>
#### com.apple.MobileAsset.AXBackTapModel
Usage: Back tap feature for iPhone. <br>
Availability: mesu only <br>
mesu.apple.com link: `https://mesu.apple.com/assets/com_apple_MobileAsset_AXBackTapModel/com_apple_MobileAsset_AXBackTapModel.xml` <br>
#### com.apple.MobileAsset.AXElementVision
Usage: Camera text recognition? <br>
Availability: hybrid (both mesu and pallas) <br>
mesu.apple.com link: `https://mesu.apple.com/assets/com_apple_MobileAsset_AXElementVision/com_apple_MobileAsset_AXElementVision.xml` <br>
Pallas example curl command:
`curl -H 'Content-Type: application/json' -H 'Accept: application/json' https://gdmf.apple.com/v2/assets --data '{"AssetAudience":"0c88076f-c292-4dad-95e7-304db9d29d34","AssetType":"com.apple.MobileAsset.AXElementVision","ClientVersion":2}'` <br>
#### com.apple.MobileAsset.AXIconVision
Usage: Back tap feature for iPhone. <br>
Availability: mesu only <br>
mesu.apple.com link: `https://mesu.apple.com/assets/com_apple_MobileAsset_AXIconVision/com_apple_MobileAsset_AXIconVision.xml` <br>
#### com.apple.MobileAsset.AXSoundActions
Usage: Includes wowel sounds. <br>
Availability: mesu only <br>
mesu.apple.com link: `https://mesu.apple.com/assets/com_apple_MobileAsset_AXSoundActions/com_apple_MobileAsset_AXSoundActions.xml` <br>
#### com.apple.MobileAsset.BridgeAssets
Usage: Apple Watch assets. <br>
Availability: hybrid (both mesu and pallas) <br>
WARNING: the response will be large both on mesu and pallas! <br>
mesu.apple.com link: `https://mesu.apple.com/assets/com_apple_MobileAsset_AXElementVision/com_apple_MobileAsset_AXElementVision.xml` <br>
Pallas example curl command:
`curl -H 'Content-Type: application/json' -H 'Accept: application/json' https://gdmf.apple.com/v2/assets --data '{"AssetAudience":"0c88076f-c292-4dad-95e7-304db9d29d34","AssetType":"com.apple.MobileAsset.BridgeAssets","ClientVersion":2}'` <br>
#### com.apple.MobileAsset.CarExperienceAssets
Usage: CarPlay asset. <br>
Availability: mesu only <br>
mesu.apple.com link: `https://mesu.apple.com/assets/com_apple_MobileAsset_CarExperienceAssets/com_apple_MobileAsset_CarExperienceAssets.xml` <br>
#### com.apple.MobileAsset.CarPlayAppBlacklist
Usage: CarPlay app blacklist. <br>
Availability: mesu only <br>
mesu.apple.com link: `https://mesu.apple.com/assets/com_apple_MobileAsset_CarPlayAppBlacklist/com_apple_MobileAsset_CarPlayAppBlacklist.xml` <br>
#### com.apple.MobileAsset.CertificatePinning
Usage: Certificate pinning asset. <br>
Availability: mesu only <br>
mesu.apple.com link: `https://mesu.apple.com/assets/com_apple_MobileAsset_CertificatePinning/com_apple_MobileAsset_CertificatePinning.xml` <br>
#### com.apple.MobileAsset.ComfortSoundsAssets
Usage: Background sounds feature. <br>
Availability: mesu only <br>
mesu.apple.com link: `https://mesu.apple.com/assets/com_apple_MobileAsset_ComfortSoundsAssets/com_apple_MobileAsset_ComfortSoundsAssets.xml` <br>
#### com.apple.MobileAsset.ContextKit
Usage: Unknown. <br>
Availability: mesu only <br>
mesu.apple.com link: `https://mesu.apple.com/assets/com_apple_MobileAsset_ContextKit/com_apple_MobileAsset_ContextKit.xml` <br>
#### com.apple.MobileAsset.CoreAS
Usage: Unknown. <br>
Availability: mesu only <br>
mesu.apple.com link: `https://mesu.apple.com/assets/com_apple_MobileAsset_CoreAS/com_apple_MobileAsset_CoreAS.xml` <br>
#### com.apple.MobileAsset.CoreIDVAssets
Usage: Root certificates. <br>
Availability: mesu only <br>
mesu.apple.com link: `https://mesu.apple.com/assets/com_apple_MobileAsset_CoreIDVAssets/com_apple_MobileAsset_CoreIDVAssets.xml` <br>
#### com.apple.MobileAsset.CoreSuggestions
Usage: Machine Learning models for suggestions. <br>
Availability: hybrid (both mesu and pallas) <br>
WARNING: the response will be large both on mesu and pallas! <br>
mesu.apple.com link: `https://mesu.apple.com/assets/com_apple_MobileAsset_CoreSuggestions/com_apple_MobileAsset_CoreSuggestions.xml` <br>
Pallas example curl command:
`curl -H 'Content-Type: application/json' -H 'Accept: application/json' https://gdmf.apple.com/v2/assets --data '{"AssetAudience":"0c88076f-c292-4dad-95e7-304db9d29d34","AssetType":"com.apple.MobileAsset.CoreSuggestions","ClientVersion":2}'` <br>
#### com.apple.MobileAsset.CoreSuggestionsModels
Usage: Other models. <br>
Availability: mesu only <br>
mesu.apple.com link: `https://mesu.apple.com/assets/com_apple_MobileAsset_CoreSuggestionsModels/com_apple_MobileAsset_CoreSuggestionsModels.xml` <br>
#### com.apple.MobileAsset.CoreSuggestionsQPAssets
Usage: Other models. <br>
Availability: mesu only <br>
mesu.apple.com link: `https://mesu.apple.com/assets/com_apple_MobileAsset_CoreSuggestionsQPAssets/com_apple_MobileAsset_CoreSuggestionsQPAssets.xml` <br>
#### com.apple.MobileAsset.DictionaryServices.dictionary
Usage: Older dictionary assets. <br>
Availability: mesu only <br>
mesu.apple.com link: `https://mesu.apple.com/assets/com_apple_MobileAsset_DictionaryServices_dictionary/com_apple_MobileAsset_DictionaryServices_dictionary.xml` <br>
#### com.apple.MobileAsset.DictionaryServices.dictionary2
Usage: Dictionary assets. <br>
Availability: mesu only <br>
WARNING: the response will be large! <br>
mesu.apple.com link: `https://mesu.apple.com/assets/com_apple_MobileAsset_DictionaryServices_dictionary2/com_apple_MobileAsset_DictionaryServices_dictionary2.xml` <br>
#### com.apple.MobileAsset.DuetExpertCenterAsset
Usage: ML assets. <br>
Availability: mesu only <br>
mesu.apple.com link: `https://mesu.apple.com/assets/com_apple_MobileAsset_DuetExpertCenterAsset/com_apple_MobileAsset_DuetExpertCenterAsset.xml` <br>
#### com.apple.MobileAsset.EmbeddedNL
Usage: Siri assets. <br>
Availability: mesu only <br>
mesu.apple.com link: `https://mesu.apple.com/assets/com_apple_MobileAsset_EmbeddedNL/com_apple_MobileAsset_EmbeddedNL.xml` <br>
#### com.apple.MobileAsset.EmbeddedSpeech
Usage: Dictation? <br>
Availability: mesu only <br>
mesu.apple.com link: `https://mesu.apple.com/assets/com_apple_MobileAsset_EmbeddedSpeech/com_apple_MobileAsset_EmbeddedSpeech.xml` <br>
#### com.apple.MobileAsset.Font
Variants:
#### com.apple.MobileAsset.Font
#### com.apple.MobileAsset.Font2
#### com.apple.MobileAsset.Font3
#### com.apple.MobileAsset.Font4
#### com.apple.MobileAsset.Font5
#### com.apple.MobileAsset.Font6
#### com.apple.MobileAsset.Font7
Usage: Font files. <br>
Availability: mesu only <br>
WARNING: the response will be large! <br>
mesu.apple.com link for Font7: `https://mesu.apple.com/assets/com_apple_MobileAsset_Font7/com_apple_MobileAsset_Font7.xml` <br>
#### com.apple.MobileAsset.GeoPolygonDataAssets
Usage: Assets for Apple Maps (most assets are on a different server). <br>
Availability: mesu only <br>
WARNING: the response will be large! <br>
mesu.apple.com link: `https://mesu.apple.com/assets/com_apple_MobileAsset_GeoPolygonDataAssets/com_apple_MobileAsset_GeoPolygonDataAssets.xml` <br>
#### com.apple.MobileAsset.Health
Usage: Assets for the Health app. <br>
Availability: mesu only <br>
WARNING: the response will be large! <br>
mesu.apple.com link: `https://mesu.apple.com/assets/com_apple_MobileAsset_Health/com_apple_MobileAsset_Health.xml` <br>
#### com.apple.MobileAsset.HealthKit.FeatureAvailability
Usage: Health feature compatibility list. <br>
Availability: mesu only <br>
mesu.apple.com link: `https://mesu.apple.com/assets/com_apple_MobileAsset_HealthKit_FeatureAvailability/com_apple_MobileAsset_HealthKit_FeatureAvailability.xml` <br>
#### com.apple.MobileAsset.HealthKit.Ontology
Usage: Ontology archive. <br>
Availability: mesu only <br>
mesu.apple.com link: `https://mesu.apple.com/assets/com_apple_MobileAsset_HealthKit_Ontology/com_apple_MobileAsset_HealthKit_Ontology.xml` <br>
#### com.apple.MobileAsset.HomeKit
Usage: HapDefinitions. <br>
Availability: mesu only <br>
mesu.apple.com link: `https://mesu.apple.com/assets/com_apple_MobileAsset_HomeKit/com_apple_MobileAsset_HomeKit.xml` <br>
#### com.apple.MobileAsset.ImageCaptionModel
Usage: VoiceOver asset. <br>
Availability: mesu only <br>
mesu.apple.com link: `https://mesu.apple.com/assets/com_apple_MobileAsset_ImageCaptionModel/com_apple_MobileAsset_ImageCaptionModel.xml` <br>
#### com.apple.MobileAsset.LanguageDetectorAssets
Usage: Language detector for Translate app. <br>
Availability: mesu only <br>
mesu.apple.com link: `https://mesu.apple.com/assets/com_apple_MobileAsset_LanguageDetectorAssets/com_apple_MobileAsset_LanguageDetectorAssets.xml` <br>
#### com.apple.MobileAsset.LinguisticData
Usage: Data for other languages (for dictation and etc.). <br>
Availability: mesu only <br>
mesu.apple.com link: `https://mesu.apple.com/assets/com_apple_MobileAsset_LinguisticData/com_apple_MobileAsset_LinguisticData.xml` <br>
#### com.apple.MobileAsset.MacinTalkVoiceAssets
Usage: Text to Speech voices. <br>
Availability: mesu only <br>
mesu.apple.com link: `https://mesu.apple.com/assets/com_apple_MobileAsset_MacinTalkVoiceAssets/com_apple_MobileAsset_MacinTalkVoiceAssets.xml` <br>
#### com.apple.MobileAsset.MagnifierAsset
Usage: Accessibility features for the Magnifier app. <br>
Availability: mesu only <br>
mesu.apple.com link: `https://mesu.apple.com/assets/com_apple_MobileAsset_MagnifierAsset/com_apple_MobileAsset_MagnifierAsset.xml` <br>
#### com.apple.MobileAsset.MediaSupport
Usage: Apple Support articles about HEVC/HEIF formats. <br>
Availability: mesu only <br>
mesu.apple.com link: `https://mesu.apple.com/assets/com_apple_MobileAsset_MediaSupport/com_apple_MobileAsset_MediaSupport.xml` <br>
#### com.apple.MobileAsset.MorphunData
Usage: Siri related. <br>
Availability: mesu only <br>
mesu.apple.com link: `https://mesu.apple.com/assets/com_apple_MobileAsset_MorphunData/com_apple_MobileAsset_MorphunData.xml` <br>
#### com.apple.MobileAsset.MXLongFormVideoApps
Usage: List of media apps for the TV app. <br>
Availability: mesu only <br>
mesu.apple.com link: `https://mesu.apple.com/assets/com_apple_MobileAsset_MXLongFormVideoApps/com_apple_MobileAsset_MXLongFormVideoApps.xml` <br>
#### com.apple.MobileAsset.MXLongFormVideoAppsV2
Usage: List of media apps for the TV app. <br>
Availability: mesu only <br>
mesu.apple.com link: `https://mesu.apple.com/assets/com_apple_MobileAsset_MXLongFormVideoAppsV2/com_apple_MobileAsset_MXLongFormVideoAppsV2.xml` <br>

To be continued...
