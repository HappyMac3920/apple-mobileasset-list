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
Usage: Camera text recognition?. <br>
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

To be continued...
