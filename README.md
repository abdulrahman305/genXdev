<hr/>

<img src="powershell.jpg" alt="GenXdev" width="50%"/>

<hr/>

### NAME
    GenXdev Powershell Modules
### SYNOPSIS
    GenXdev PowerShell Utilities and helpers
[![GenXdev](https://img.shields.io/powershellgallery/v/GenXdev.svg?style=flat-square&label=GenXdev)](https://www.powershellgallery.com/packages/GenXdev/) [![License](https://img.shields.io/github/license/genXdev/GenXdev?style=flat-square)](./LICENSE)

## APACHE 2.0 License

````text
Copyright (c) 2025 René Vaessen / GenXdev

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

     http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

````

# Modules

## Module Overview

| Module | Description | Repository |
| :--- | :--- | :--- |
| [GenXdev.AI](#genxdevai) | A Windows PowerShell module for local AI related operations | [📁 GenXdev.AI](https://github.com/genXdev/GenXdev.AI) |
| [GenXdev.Coding](#genxdevcoding) | A Windows PowerShell module that helps being more productive with coding tasks. | [📁 GenXdev.Coding](https://github.com/genXdev/GenXdev.Coding) |
| [GenXdev.Console](#genxdevconsole) | A Windows PowerShell module for enhancing the commandline experience | [📁 GenXdev.Console](https://github.com/genXdev/GenXdev.Console) |
| [GenXdev.Data](#genxdevdata) | A Windows PowerShell module for enhancing the commandline experience | [📁 GenXdev.Data](https://github.com/genXdev/GenXdev.Data) |
| [GenXdev.FileSystem](#genxdevfilesystem) | A Windows PowerShell module for basic and advanced file management tasks | [📁 GenXdev.FileSystem](https://github.com/genXdev/GenXdev.FileSystem) |
| [GenXdev.Helpers](#genxdevhelpers) | A Windows PowerShell module with helpers mostly used by other GenXdev modules | [📁 GenXdev.Helpers](https://github.com/genXdev/GenXdev.Helpers) |
| [GenXdev.Media](#genxdevmedia) | A Windows PowerShell module that helps with converting media files like pictures and video files | [📁 GenXdev.Media](https://github.com/genXdev/GenXdev.Media) |
| [GenXdev.Queries](#genxdevqueries) | A Windows PowerShell module for finding resources and information on the internet | [📁 GenXdev.Queries](https://github.com/genXdev/GenXdev.Queries) |
| [GenXdev.Webbrowser](#genxdevwebbrowser) | &nbsp; | [📁 GenXdev.Webbrowser](https://github.com/genXdev/GenXdev.Webbrowser) |
| [GenXdev.Windows](#genxdevwindows) | &nbsp; | [📁 GenXdev.Windows](https://github.com/genXdev/GenXdev.Windows) |

<br/><hr/><br/>

## GenXdev.AI

**A Windows PowerShell module for local AI related operations**

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [Add-EmoticonsToText](https://github.com/genXdev/GenXdev.AI/tree/main#add-emoticonstotext) | emojify | &nbsp; |
| [Add-GenXdevMCPServerToLMStudio](https://github.com/genXdev/GenXdev.AI/tree/main#add-genxdevmcpservertolmstudio) | &nbsp; | Adds the GenXdev MCP server to LM Studio using a deeplink configuration. |
| [Add-ImageDirectories](https://github.com/genXdev/GenXdev.AI/tree/main#add-imagedirectories) | addimgdir | Adds directories to the configured image directories for GenXdev.AI operations. |
| [Approve-NewTextFileContent](https://github.com/genXdev/GenXdev.AI/tree/main#approve-newtextfilecontent) | &nbsp; | Interactive file content comparison and approval using WinMerge. |
| [Compare-ImageFaces](https://github.com/genXdev/GenXdev.AI/tree/main#compare-imagefaces) | comparefaces | &nbsp; |
| [Convert-DotNetTypeToLLMType](https://github.com/genXdev/GenXdev.AI/tree/main#convert-dotnettypetollmtype) | &nbsp; | Converts .NET type names to LLM (Language Model) type names. |
| [ConvertComfyImageFormat](https://github.com/genXdev/GenXdev.AI/tree/main#convertcomfyimageformat) | &nbsp; | Converts image file format while preserving maximum quality. |
| [ConvertFrom-CorporateSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertfrom-corporatespeak) | uncorporatize | &nbsp; |
| [ConvertFrom-DiplomaticSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertfrom-diplomaticspeak) | undiplomatize | &nbsp; |
| [ConvertTo-CorporateSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertto-corporatespeak) | corporatize | &nbsp; |
| [ConvertTo-DiplomaticSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertto-diplomaticspeak) | diplomatize | &nbsp; |
| [ConvertTo-LMStudioFunctionDefinition](https://github.com/genXdev/GenXdev.AI/tree/main#convertto-lmstudiofunctiondefinition) | &nbsp; | &nbsp; |
| [CreateComfySDXLWorkflow](https://github.com/genXdev/GenXdev.AI/tree/main#createcomfysdxlworkflow) | &nbsp; | Creates comprehensive ComfyUI SDXL workflow configuration supporting all parameters |
| [CreateComfyUniversalWorkflow](https://github.com/genXdev/GenXdev.AI/tree/main#createcomfyuniversalworkflow) | &nbsp; | &nbsp; |
| [DownloadComfyResults](https://github.com/genXdev/GenXdev.AI/tree/main#downloadcomfyresults) | &nbsp; | Downloads generated results from ComfyUI server with file information |
| [EnsureComfyUI](https://github.com/genXdev/GenXdev.AI/tree/main#ensurecomfyui) | &nbsp; | Ensures ComfyUI is installed and running with optional window positioning. |
| [EnsureComfyUIModel](https://github.com/genXdev/GenXdev.AI/tree/main#ensurecomfyuimodel) | &nbsp; | Ensures specified ComfyUI models are available locally with automatic download |
| [EnsureDeepStack](https://github.com/genXdev/GenXdev.AI/tree/main#ensuredeepstack) | &nbsp; | &nbsp; |
| [EnsureGithubCLIInstalled](https://github.com/genXdev/GenXdev.AI/tree/main#ensuregithubcliinstalled) | &nbsp; | Ensures GitHub CLI is properly installed and configured on the system. |
| [EnsureHuggingFace](https://github.com/genXdev/GenXdev.AI/tree/main#ensurehuggingface) | &nbsp; | &nbsp; |
| [EnsureLMStudio](https://github.com/genXdev/GenXdev.AI/tree/main#ensurelmstudio) | &nbsp; | &nbsp; |
| [EnsurePaintNet](https://github.com/genXdev/GenXdev.AI/tree/main#ensurepaintnet) | &nbsp; | Ensures Paint.NET is properly installed and accessible on the system. |
| [EnsurePip](https://github.com/genXdev/GenXdev.AI/tree/main#ensurepip) | &nbsp; | Ensures pip is installed and functional for the specified Python installation. |
| [EnsurePython](https://github.com/genXdev/GenXdev.AI/tree/main#ensurepython) | &nbsp; | &nbsp; |
| [EnsureWinMergeInstalled](https://github.com/genXdev/GenXdev.AI/tree/main#ensurewinmergeinstalled) | &nbsp; | Ensures WinMerge is installed and available for file comparison operations. |
| [Export-ImageIndex](https://github.com/genXdev/GenXdev.AI/tree/main#export-imageindex) | indeximages | &nbsp; |
| [Find-Image](https://github.com/genXdev/GenXdev.AI/tree/main#find-image) | findimages, li | &nbsp; |
| [Find-IndexedImage](https://github.com/genXdev/GenXdev.AI/tree/main#find-indexedimage) | findindexedimages, lii | &nbsp; |
| [GenerateMasonryLayoutHtml](https://github.com/genXdev/GenXdev.AI/tree/main#generatemasonrylayouthtml) | &nbsp; | Generates a responsive masonry layout HTML gallery from image data. |
| [Get-AIDefaultLLMSettings](https://github.com/genXdev/GenXdev.AI/tree/main#get-aidefaultllmsettings) | &nbsp; | &nbsp; |
| [Get-AIImageCollection](https://github.com/genXdev/GenXdev.AI/tree/main#get-aiimagecollection) | getimgdirs | &nbsp; |
| [Get-AIKnownFacesRootpath](https://github.com/genXdev/GenXdev.AI/tree/main#get-aiknownfacesrootpath) | &nbsp; | Gets the configured directory for face image files used in GenXdev.AI operations. |
| [Get-AILLMSettings](https://github.com/genXdev/GenXdev.AI/tree/main#get-aillmsettings) | &nbsp; | &nbsp; |
| [Get-AIMetaLanguage](https://github.com/genXdev/GenXdev.AI/tree/main#get-aimetalanguage) | getimgmetalang | Gets the configured default language for image metadata operations. |
| [Get-ComfyUIModelPath](https://github.com/genXdev/GenXdev.AI/tree/main#get-comfyuimodelpath) | &nbsp; | Gets the correct ComfyUI models directory path for the current installation |
| [Get-CpuCore](https://github.com/genXdev/GenXdev.AI/tree/main#get-cpucore) | &nbsp; | Calculates and returns the total number of logical CPU cores in the system. |
| [Get-Fallacy](https://github.com/genXdev/GenXdev.AI/tree/main#get-fallacy) | dispicetext | &nbsp; |
| [Get-HasCapableGpu](https://github.com/genXdev/GenXdev.AI/tree/main#get-hascapablegpu) | &nbsp; | Determines if a CUDA-capable GPU with sufficient memory is present. |
| [Get-ImageDetectedFaces](https://github.com/genXdev/GenXdev.AI/tree/main#get-imagedetectedfaces) | &nbsp; | &nbsp; |
| [Get-ImageDetectedObjects](https://github.com/genXdev/GenXdev.AI/tree/main#get-imagedetectedobjects) | &nbsp; | Detects and classifies objects in an uploaded image using DeepStack. |
| [Get-ImageDetectedScenes](https://github.com/genXdev/GenXdev.AI/tree/main#get-imagedetectedscenes) | &nbsp; | &nbsp; |
| [Get-ImageIndexPath](https://github.com/genXdev/GenXdev.AI/tree/main#get-imageindexpath) | &nbsp; | Returns the path to the image database, initializing or rebuilding it if needed. |
| [Get-ImageIndexStats](https://github.com/genXdev/GenXdev.AI/tree/main#get-imageindexstats) | getimagedbstats, gids | &nbsp; |
| [Get-LMStudioLoadedModelList](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudioloadedmodellist) | &nbsp; | Retrieves the list of currently loaded models from LM Studio. |
| [Get-LMStudioModelList](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiomodellist) | &nbsp; | Retrieves a list of installed LM Studio models. |
| [Get-LMStudioPaths](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiopaths) | &nbsp; | Retrieves file paths for LM Studio executables. |
| [Get-LMStudioTextEmbedding](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiotextembedding) | &nbsp; | Gets text embeddings from LM Studio model. |
| [Get-LMStudioWindow](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiowindow) | lmstudiowindow, setlmstudiowindow | Gets a window helper for the LM Studio application. |
| [Get-NumberOfCpuCores](https://github.com/genXdev/GenXdev.AI/tree/main#get-numberofcpucores) | &nbsp; | Calculates and returns the total number of logical CPU cores in the system. |
| [Get-RegisteredFaces](https://github.com/genXdev/GenXdev.AI/tree/main#get-registeredfaces) | &nbsp; | &nbsp; |
| [Get-ScriptExecutionErrorFixPrompt](https://github.com/genXdev/GenXdev.AI/tree/main#get-scriptexecutionerrorfixprompt) | getfixprompt | &nbsp; |
| [Get-SimularMovieTitles](https://github.com/genXdev/GenXdev.AI/tree/main#get-simularmovietitles) | &nbsp; | Finds similar movie titles based on common properties. |
| [Get-TextTranslation](https://github.com/genXdev/GenXdev.AI/tree/main#get-texttranslation) | translate | &nbsp; |
| [Get-VectorSimilarity](https://github.com/genXdev/GenXdev.AI/tree/main#get-vectorsimilarity) | &nbsp; | Calculates the cosine similarity between two vectors, returning a value between 0 and 1. |
| [Initialize-LMStudioModel](https://github.com/genXdev/GenXdev.AI/tree/main#initialize-lmstudiomodel) | initlmstudio | &nbsp; |
| [Install-LMStudioApplication](https://github.com/genXdev/GenXdev.AI/tree/main#install-lmstudioapplication) | &nbsp; | Installs LM Studio application using WinGet package manager. |
| [Invoke-AIPowershellCommand](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-aipowershellcommand) | hint | &nbsp; |
| [Invoke-ComfyUIImageGeneration](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-comfyuiimagegeneration) | generateimage | &nbsp; |
| [Invoke-CommandFromToolCall](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-commandfromtoolcall) | &nbsp; | &nbsp; |
| [Invoke-HuggingFaceCli](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-huggingfacecli) | &nbsp; | &nbsp; |
| [Invoke-ImageEnhancement](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imageenhancement) | enhanceimage | &nbsp; |
| [Invoke-ImageFacesUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagefacesupdate) | imagepeopledetection | &nbsp; |
| [Invoke-ImageKeywordUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagekeywordupdate) | imagekeywordgeneration | &nbsp; |
| [Invoke-ImageMetadataUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagemetadataupdate) | imagepropdetection | &nbsp; |
| [Invoke-ImageObjectsUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imageobjectsupdate) | imageobjectdetection | &nbsp; |
| [Invoke-ImageScenesUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagescenesupdate) | imagescenedetection | &nbsp; |
| [Invoke-LLMBooleanEvaluation](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmbooleanevaluation) | equalstrue | &nbsp; |
| [Invoke-LLMQuery](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmquery) | llm, qllm | &nbsp; |
| [Invoke-LLMStringListEvaluation](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmstringlistevaluation) | getlist, getstring | &nbsp; |
| [Invoke-LLMTextTransformation](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmtexttransformation) | spellcheck | &nbsp; |
| [Invoke-QueryImageContent](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-queryimagecontent) | &nbsp; | &nbsp; |
| [Invoke-WinMerge](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-winmerge) | &nbsp; | Launches WinMerge to compare two files side by side. |
| [New-LLMAudioChat](https://github.com/genXdev/GenXdev.AI/tree/main#new-llmaudiochat) | llmaudiochat | &nbsp; |
| [New-LLMTextChat](https://github.com/genXdev/GenXdev.AI/tree/main#new-llmtextchat) | llmchat | &nbsp; |
| [QueueComfyWorkflow](https://github.com/genXdev/GenXdev.AI/tree/main#queuecomfyworkflow) | &nbsp; | &nbsp; |
| [Register-AllFaces](https://github.com/genXdev/GenXdev.AI/tree/main#register-allfaces) | UpdateFaces | &nbsp; |
| [Register-Face](https://github.com/genXdev/GenXdev.AI/tree/main#register-face) | &nbsp; | &nbsp; |
| [Remove-ImageDirectories](https://github.com/genXdev/GenXdev.AI/tree/main#remove-imagedirectories) | removeimgdir | &nbsp; |
| [Remove-ImageMetaData](https://github.com/genXdev/GenXdev.AI/tree/main#remove-imagemetadata) | removeimagedata | &nbsp; |
| [ResizeComfyInputImage](https://github.com/genXdev/GenXdev.AI/tree/main#resizecomfyinputimage) | &nbsp; | &nbsp; |
| [Save-FoundImageFaces](https://github.com/genXdev/GenXdev.AI/tree/main#save-foundimagefaces) | saveimagefaces | &nbsp; |
| [Save-FoundImageObjects](https://github.com/genXdev/GenXdev.AI/tree/main#save-foundimageobjects) | saveimageObjects | &nbsp; |
| [Save-Transcriptions](https://github.com/genXdev/GenXdev.AI/tree/main#save-transcriptions) | &nbsp; | &nbsp; |
| [Set-AIImageCollection](https://github.com/genXdev/GenXdev.AI/tree/main#set-aiimagecollection) | &nbsp; | &nbsp; |
| [Set-AIKnownFacesRootpath](https://github.com/genXdev/GenXdev.AI/tree/main#set-aiknownfacesrootpath) | &nbsp; | Sets the directory for face image files used in GenXdev.AI operations. |
| [Set-AILLMSettings](https://github.com/genXdev/GenXdev.AI/tree/main#set-aillmsettings) | &nbsp; | &nbsp; |
| [Set-AIMetaLanguage](https://github.com/genXdev/GenXdev.AI/tree/main#set-aimetalanguage) | &nbsp; | Sets the default language and optionally the image directories for GenXdev.AI image metadata operations. |
| [Set-ComfyUIBackgroundImage](https://github.com/genXdev/GenXdev.AI/tree/main#set-comfyuibackgroundimage) | &nbsp; | Sets or clears the background image for ComfyUI's canvas interface |
| [Set-ComfyUIModelPath](https://github.com/genXdev/GenXdev.AI/tree/main#set-comfyuimodelpath) | &nbsp; | &nbsp; |
| [Set-GenXdevAICommandNotFoundAction](https://github.com/genXdev/GenXdev.AI/tree/main#set-genxdevaicommandnotfoundaction) | &nbsp; | &nbsp; |
| [Set-ImageIndexPath](https://github.com/genXdev/GenXdev.AI/tree/main#set-imageindexpath) | &nbsp; | Sets the default database file path for image operations in GenXdev.AI. |
| [Set-WindowsWallpaperEx](https://github.com/genXdev/GenXdev.AI/tree/main#set-windowswallpaperex) | nextwallpaper | &nbsp; |
| [SetComfyUIProcessPriority](https://github.com/genXdev/GenXdev.AI/tree/main#setcomfyuiprocesspriority) | &nbsp; | &nbsp; |
| [Show-FoundImagesInBrowser](https://github.com/genXdev/GenXdev.AI/tree/main#show-foundimagesinbrowser) | showfoundimages | &nbsp; |
| [Show-GenXdevScriptErrorFixInIde](https://github.com/genXdev/GenXdev.AI/tree/main#show-genxdevscripterrorfixinide) | letsfixthis | &nbsp; |
| [Start-AudioTranscription](https://github.com/genXdev/GenXdev.AI/tree/main#start-audiotranscription) | transcribe, transcribefile | &nbsp; |
| [Start-GenXdevMCPServer](https://github.com/genXdev/GenXdev.AI/tree/main#start-genxdevmcpserver) | &nbsp; | &nbsp; |
| [Start-LMStudioApplication](https://github.com/genXdev/GenXdev.AI/tree/main#start-lmstudioapplication) | &nbsp; | Starts the LM Studio application if it's not already running. |
| [Stop-ComfyUI](https://github.com/genXdev/GenXdev.AI/tree/main#stop-comfyui) | &nbsp; | Terminates all running ComfyUI processes and releases associated resources. |
| [Test-ComfyUIQueueEmpty](https://github.com/genXdev/GenXdev.AI/tree/main#test-comfyuiqueueempty) | &nbsp; | Checks if the ComfyUI processing queue is empty |
| [Test-DeepLinkImageFile](https://github.com/genXdev/GenXdev.AI/tree/main#test-deeplinkimagefile) | &nbsp; | Tests if the specified file path is a valid image file with a supported format. |
| [Test-LMStudioInstallation](https://github.com/genXdev/GenXdev.AI/tree/main#test-lmstudioinstallation) | &nbsp; | Tests if LMStudio is installed and accessible on the system. |
| [Test-LMStudioProcess](https://github.com/genXdev/GenXdev.AI/tree/main#test-lmstudioprocess) | &nbsp; | Tests if LM Studio process is running and configures its window state. |
| [Unregister-AllFaces](https://github.com/genXdev/GenXdev.AI/tree/main#unregister-allfaces) | &nbsp; | Removes all registered faces from the DeepStack face recognition system. |
| [Unregister-Face](https://github.com/genXdev/GenXdev.AI/tree/main#unregister-face) | &nbsp; | Deletes a registered face by its identifier from DeepStack. |
| [Update-AllImageMetaData](https://github.com/genXdev/GenXdev.AI/tree/main#update-allimagemetadata) | updateallimages | &nbsp; |
| [UploadComfyImage](https://github.com/genXdev/GenXdev.AI/tree/main#uploadcomfyimage) | &nbsp; | &nbsp; |
| [WaitForComfyCompletion](https://github.com/genXdev/GenXdev.AI/tree/main#waitforcomfycompletion) | &nbsp; | &nbsp; |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.AI/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.AI.ComfyUI

**A Windows PowerShell module for local AI related operations**

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [Add-EmoticonsToText](https://github.com/genXdev/GenXdev.AI/tree/main#add-emoticonstotext) | emojify | &nbsp; |
| [Add-GenXdevMCPServerToLMStudio](https://github.com/genXdev/GenXdev.AI/tree/main#add-genxdevmcpservertolmstudio) | &nbsp; | Adds the GenXdev MCP server to LM Studio using a deeplink configuration. |
| [Add-ImageDirectories](https://github.com/genXdev/GenXdev.AI/tree/main#add-imagedirectories) | addimgdir | Adds directories to the configured image directories for GenXdev.AI operations. |
| [Approve-NewTextFileContent](https://github.com/genXdev/GenXdev.AI/tree/main#approve-newtextfilecontent) | &nbsp; | Interactive file content comparison and approval using WinMerge. |
| [Compare-ImageFaces](https://github.com/genXdev/GenXdev.AI/tree/main#compare-imagefaces) | comparefaces | &nbsp; |
| [Convert-DotNetTypeToLLMType](https://github.com/genXdev/GenXdev.AI/tree/main#convert-dotnettypetollmtype) | &nbsp; | Converts .NET type names to LLM (Language Model) type names. |
| [ConvertComfyImageFormat](https://github.com/genXdev/GenXdev.AI/tree/main#convertcomfyimageformat) | &nbsp; | Converts image file format while preserving maximum quality. |
| [ConvertFrom-CorporateSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertfrom-corporatespeak) | uncorporatize | &nbsp; |
| [ConvertFrom-DiplomaticSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertfrom-diplomaticspeak) | undiplomatize | &nbsp; |
| [ConvertTo-CorporateSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertto-corporatespeak) | corporatize | &nbsp; |
| [ConvertTo-DiplomaticSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertto-diplomaticspeak) | diplomatize | &nbsp; |
| [ConvertTo-LMStudioFunctionDefinition](https://github.com/genXdev/GenXdev.AI/tree/main#convertto-lmstudiofunctiondefinition) | &nbsp; | &nbsp; |
| [CreateComfySDXLWorkflow](https://github.com/genXdev/GenXdev.AI/tree/main#createcomfysdxlworkflow) | &nbsp; | Creates comprehensive ComfyUI SDXL workflow configuration supporting all parameters |
| [CreateComfyUniversalWorkflow](https://github.com/genXdev/GenXdev.AI/tree/main#createcomfyuniversalworkflow) | &nbsp; | &nbsp; |
| [DownloadComfyResults](https://github.com/genXdev/GenXdev.AI/tree/main#downloadcomfyresults) | &nbsp; | Downloads generated results from ComfyUI server with file information |
| [EnsureComfyUI](https://github.com/genXdev/GenXdev.AI/tree/main#ensurecomfyui) | &nbsp; | Ensures ComfyUI is installed and running with optional window positioning. |
| [EnsureComfyUIModel](https://github.com/genXdev/GenXdev.AI/tree/main#ensurecomfyuimodel) | &nbsp; | Ensures specified ComfyUI models are available locally with automatic download |
| [EnsureDeepStack](https://github.com/genXdev/GenXdev.AI/tree/main#ensuredeepstack) | &nbsp; | &nbsp; |
| [EnsureGithubCLIInstalled](https://github.com/genXdev/GenXdev.AI/tree/main#ensuregithubcliinstalled) | &nbsp; | Ensures GitHub CLI is properly installed and configured on the system. |
| [EnsureHuggingFace](https://github.com/genXdev/GenXdev.AI/tree/main#ensurehuggingface) | &nbsp; | &nbsp; |
| [EnsureLMStudio](https://github.com/genXdev/GenXdev.AI/tree/main#ensurelmstudio) | &nbsp; | &nbsp; |
| [EnsurePaintNet](https://github.com/genXdev/GenXdev.AI/tree/main#ensurepaintnet) | &nbsp; | Ensures Paint.NET is properly installed and accessible on the system. |
| [EnsurePip](https://github.com/genXdev/GenXdev.AI/tree/main#ensurepip) | &nbsp; | Ensures pip is installed and functional for the specified Python installation. |
| [EnsurePython](https://github.com/genXdev/GenXdev.AI/tree/main#ensurepython) | &nbsp; | &nbsp; |
| [EnsureWinMergeInstalled](https://github.com/genXdev/GenXdev.AI/tree/main#ensurewinmergeinstalled) | &nbsp; | Ensures WinMerge is installed and available for file comparison operations. |
| [Export-ImageIndex](https://github.com/genXdev/GenXdev.AI/tree/main#export-imageindex) | indeximages | &nbsp; |
| [Find-Image](https://github.com/genXdev/GenXdev.AI/tree/main#find-image) | findimages, li | &nbsp; |
| [Find-IndexedImage](https://github.com/genXdev/GenXdev.AI/tree/main#find-indexedimage) | findindexedimages, lii | &nbsp; |
| [GenerateMasonryLayoutHtml](https://github.com/genXdev/GenXdev.AI/tree/main#generatemasonrylayouthtml) | &nbsp; | Generates a responsive masonry layout HTML gallery from image data. |
| [Get-AIDefaultLLMSettings](https://github.com/genXdev/GenXdev.AI/tree/main#get-aidefaultllmsettings) | &nbsp; | &nbsp; |
| [Get-AIImageCollection](https://github.com/genXdev/GenXdev.AI/tree/main#get-aiimagecollection) | getimgdirs | &nbsp; |
| [Get-AIKnownFacesRootpath](https://github.com/genXdev/GenXdev.AI/tree/main#get-aiknownfacesrootpath) | &nbsp; | Gets the configured directory for face image files used in GenXdev.AI operations. |
| [Get-AILLMSettings](https://github.com/genXdev/GenXdev.AI/tree/main#get-aillmsettings) | &nbsp; | &nbsp; |
| [Get-AIMetaLanguage](https://github.com/genXdev/GenXdev.AI/tree/main#get-aimetalanguage) | getimgmetalang | Gets the configured default language for image metadata operations. |
| [Get-ComfyUIModelPath](https://github.com/genXdev/GenXdev.AI/tree/main#get-comfyuimodelpath) | &nbsp; | Gets the correct ComfyUI models directory path for the current installation |
| [Get-CpuCore](https://github.com/genXdev/GenXdev.AI/tree/main#get-cpucore) | &nbsp; | Calculates and returns the total number of logical CPU cores in the system. |
| [Get-Fallacy](https://github.com/genXdev/GenXdev.AI/tree/main#get-fallacy) | dispicetext | &nbsp; |
| [Get-HasCapableGpu](https://github.com/genXdev/GenXdev.AI/tree/main#get-hascapablegpu) | &nbsp; | Determines if a CUDA-capable GPU with sufficient memory is present. |
| [Get-ImageDetectedFaces](https://github.com/genXdev/GenXdev.AI/tree/main#get-imagedetectedfaces) | &nbsp; | &nbsp; |
| [Get-ImageDetectedObjects](https://github.com/genXdev/GenXdev.AI/tree/main#get-imagedetectedobjects) | &nbsp; | Detects and classifies objects in an uploaded image using DeepStack. |
| [Get-ImageDetectedScenes](https://github.com/genXdev/GenXdev.AI/tree/main#get-imagedetectedscenes) | &nbsp; | &nbsp; |
| [Get-ImageIndexPath](https://github.com/genXdev/GenXdev.AI/tree/main#get-imageindexpath) | &nbsp; | Returns the path to the image database, initializing or rebuilding it if needed. |
| [Get-ImageIndexStats](https://github.com/genXdev/GenXdev.AI/tree/main#get-imageindexstats) | getimagedbstats, gids | &nbsp; |
| [Get-LMStudioLoadedModelList](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudioloadedmodellist) | &nbsp; | Retrieves the list of currently loaded models from LM Studio. |
| [Get-LMStudioModelList](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiomodellist) | &nbsp; | Retrieves a list of installed LM Studio models. |
| [Get-LMStudioPaths](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiopaths) | &nbsp; | Retrieves file paths for LM Studio executables. |
| [Get-LMStudioTextEmbedding](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiotextembedding) | &nbsp; | Gets text embeddings from LM Studio model. |
| [Get-LMStudioWindow](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiowindow) | lmstudiowindow, setlmstudiowindow | Gets a window helper for the LM Studio application. |
| [Get-NumberOfCpuCores](https://github.com/genXdev/GenXdev.AI/tree/main#get-numberofcpucores) | &nbsp; | Calculates and returns the total number of logical CPU cores in the system. |
| [Get-RegisteredFaces](https://github.com/genXdev/GenXdev.AI/tree/main#get-registeredfaces) | &nbsp; | &nbsp; |
| [Get-ScriptExecutionErrorFixPrompt](https://github.com/genXdev/GenXdev.AI/tree/main#get-scriptexecutionerrorfixprompt) | getfixprompt | &nbsp; |
| [Get-SimularMovieTitles](https://github.com/genXdev/GenXdev.AI/tree/main#get-simularmovietitles) | &nbsp; | Finds similar movie titles based on common properties. |
| [Get-TextTranslation](https://github.com/genXdev/GenXdev.AI/tree/main#get-texttranslation) | translate | &nbsp; |
| [Get-VectorSimilarity](https://github.com/genXdev/GenXdev.AI/tree/main#get-vectorsimilarity) | &nbsp; | Calculates the cosine similarity between two vectors, returning a value between 0 and 1. |
| [Initialize-LMStudioModel](https://github.com/genXdev/GenXdev.AI/tree/main#initialize-lmstudiomodel) | initlmstudio | &nbsp; |
| [Install-LMStudioApplication](https://github.com/genXdev/GenXdev.AI/tree/main#install-lmstudioapplication) | &nbsp; | Installs LM Studio application using WinGet package manager. |
| [Invoke-AIPowershellCommand](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-aipowershellcommand) | hint | &nbsp; |
| [Invoke-ComfyUIImageGeneration](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-comfyuiimagegeneration) | generateimage | &nbsp; |
| [Invoke-CommandFromToolCall](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-commandfromtoolcall) | &nbsp; | &nbsp; |
| [Invoke-HuggingFaceCli](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-huggingfacecli) | &nbsp; | &nbsp; |
| [Invoke-ImageEnhancement](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imageenhancement) | enhanceimage | &nbsp; |
| [Invoke-ImageFacesUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagefacesupdate) | imagepeopledetection | &nbsp; |
| [Invoke-ImageKeywordUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagekeywordupdate) | imagekeywordgeneration | &nbsp; |
| [Invoke-ImageMetadataUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagemetadataupdate) | imagepropdetection | &nbsp; |
| [Invoke-ImageObjectsUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imageobjectsupdate) | imageobjectdetection | &nbsp; |
| [Invoke-ImageScenesUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagescenesupdate) | imagescenedetection | &nbsp; |
| [Invoke-LLMBooleanEvaluation](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmbooleanevaluation) | equalstrue | &nbsp; |
| [Invoke-LLMQuery](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmquery) | llm, qllm | &nbsp; |
| [Invoke-LLMStringListEvaluation](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmstringlistevaluation) | getlist, getstring | &nbsp; |
| [Invoke-LLMTextTransformation](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmtexttransformation) | spellcheck | &nbsp; |
| [Invoke-QueryImageContent](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-queryimagecontent) | &nbsp; | &nbsp; |
| [Invoke-WinMerge](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-winmerge) | &nbsp; | Launches WinMerge to compare two files side by side. |
| [New-LLMAudioChat](https://github.com/genXdev/GenXdev.AI/tree/main#new-llmaudiochat) | llmaudiochat | &nbsp; |
| [New-LLMTextChat](https://github.com/genXdev/GenXdev.AI/tree/main#new-llmtextchat) | llmchat | &nbsp; |
| [QueueComfyWorkflow](https://github.com/genXdev/GenXdev.AI/tree/main#queuecomfyworkflow) | &nbsp; | &nbsp; |
| [Register-AllFaces](https://github.com/genXdev/GenXdev.AI/tree/main#register-allfaces) | UpdateFaces | &nbsp; |
| [Register-Face](https://github.com/genXdev/GenXdev.AI/tree/main#register-face) | &nbsp; | &nbsp; |
| [Remove-ImageDirectories](https://github.com/genXdev/GenXdev.AI/tree/main#remove-imagedirectories) | removeimgdir | &nbsp; |
| [Remove-ImageMetaData](https://github.com/genXdev/GenXdev.AI/tree/main#remove-imagemetadata) | removeimagedata | &nbsp; |
| [ResizeComfyInputImage](https://github.com/genXdev/GenXdev.AI/tree/main#resizecomfyinputimage) | &nbsp; | &nbsp; |
| [Save-FoundImageFaces](https://github.com/genXdev/GenXdev.AI/tree/main#save-foundimagefaces) | saveimagefaces | &nbsp; |
| [Save-FoundImageObjects](https://github.com/genXdev/GenXdev.AI/tree/main#save-foundimageobjects) | saveimageObjects | &nbsp; |
| [Save-Transcriptions](https://github.com/genXdev/GenXdev.AI/tree/main#save-transcriptions) | &nbsp; | &nbsp; |
| [Set-AIImageCollection](https://github.com/genXdev/GenXdev.AI/tree/main#set-aiimagecollection) | &nbsp; | &nbsp; |
| [Set-AIKnownFacesRootpath](https://github.com/genXdev/GenXdev.AI/tree/main#set-aiknownfacesrootpath) | &nbsp; | Sets the directory for face image files used in GenXdev.AI operations. |
| [Set-AILLMSettings](https://github.com/genXdev/GenXdev.AI/tree/main#set-aillmsettings) | &nbsp; | &nbsp; |
| [Set-AIMetaLanguage](https://github.com/genXdev/GenXdev.AI/tree/main#set-aimetalanguage) | &nbsp; | Sets the default language and optionally the image directories for GenXdev.AI image metadata operations. |
| [Set-ComfyUIBackgroundImage](https://github.com/genXdev/GenXdev.AI/tree/main#set-comfyuibackgroundimage) | &nbsp; | Sets or clears the background image for ComfyUI's canvas interface |
| [Set-ComfyUIModelPath](https://github.com/genXdev/GenXdev.AI/tree/main#set-comfyuimodelpath) | &nbsp; | &nbsp; |
| [Set-GenXdevAICommandNotFoundAction](https://github.com/genXdev/GenXdev.AI/tree/main#set-genxdevaicommandnotfoundaction) | &nbsp; | &nbsp; |
| [Set-ImageIndexPath](https://github.com/genXdev/GenXdev.AI/tree/main#set-imageindexpath) | &nbsp; | Sets the default database file path for image operations in GenXdev.AI. |
| [Set-WindowsWallpaperEx](https://github.com/genXdev/GenXdev.AI/tree/main#set-windowswallpaperex) | nextwallpaper | &nbsp; |
| [SetComfyUIProcessPriority](https://github.com/genXdev/GenXdev.AI/tree/main#setcomfyuiprocesspriority) | &nbsp; | &nbsp; |
| [Show-FoundImagesInBrowser](https://github.com/genXdev/GenXdev.AI/tree/main#show-foundimagesinbrowser) | showfoundimages | &nbsp; |
| [Show-GenXdevScriptErrorFixInIde](https://github.com/genXdev/GenXdev.AI/tree/main#show-genxdevscripterrorfixinide) | letsfixthis | &nbsp; |
| [Start-AudioTranscription](https://github.com/genXdev/GenXdev.AI/tree/main#start-audiotranscription) | transcribe, transcribefile | &nbsp; |
| [Start-GenXdevMCPServer](https://github.com/genXdev/GenXdev.AI/tree/main#start-genxdevmcpserver) | &nbsp; | &nbsp; |
| [Start-LMStudioApplication](https://github.com/genXdev/GenXdev.AI/tree/main#start-lmstudioapplication) | &nbsp; | Starts the LM Studio application if it's not already running. |
| [Stop-ComfyUI](https://github.com/genXdev/GenXdev.AI/tree/main#stop-comfyui) | &nbsp; | Terminates all running ComfyUI processes and releases associated resources. |
| [Test-ComfyUIQueueEmpty](https://github.com/genXdev/GenXdev.AI/tree/main#test-comfyuiqueueempty) | &nbsp; | Checks if the ComfyUI processing queue is empty |
| [Test-DeepLinkImageFile](https://github.com/genXdev/GenXdev.AI/tree/main#test-deeplinkimagefile) | &nbsp; | Tests if the specified file path is a valid image file with a supported format. |
| [Test-LMStudioInstallation](https://github.com/genXdev/GenXdev.AI/tree/main#test-lmstudioinstallation) | &nbsp; | Tests if LMStudio is installed and accessible on the system. |
| [Test-LMStudioProcess](https://github.com/genXdev/GenXdev.AI/tree/main#test-lmstudioprocess) | &nbsp; | Tests if LM Studio process is running and configures its window state. |
| [Unregister-AllFaces](https://github.com/genXdev/GenXdev.AI/tree/main#unregister-allfaces) | &nbsp; | Removes all registered faces from the DeepStack face recognition system. |
| [Unregister-Face](https://github.com/genXdev/GenXdev.AI/tree/main#unregister-face) | &nbsp; | Deletes a registered face by its identifier from DeepStack. |
| [Update-AllImageMetaData](https://github.com/genXdev/GenXdev.AI/tree/main#update-allimagemetadata) | updateallimages | &nbsp; |
| [UploadComfyImage](https://github.com/genXdev/GenXdev.AI/tree/main#uploadcomfyimage) | &nbsp; | &nbsp; |
| [WaitForComfyCompletion](https://github.com/genXdev/GenXdev.AI/tree/main#waitforcomfycompletion) | &nbsp; | &nbsp; |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.AI/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.AI.Data

**A Windows PowerShell module for local AI related operations**

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [Add-EmoticonsToText](https://github.com/genXdev/GenXdev.AI/tree/main#add-emoticonstotext) | emojify | &nbsp; |
| [Add-GenXdevMCPServerToLMStudio](https://github.com/genXdev/GenXdev.AI/tree/main#add-genxdevmcpservertolmstudio) | &nbsp; | Adds the GenXdev MCP server to LM Studio using a deeplink configuration. |
| [Add-ImageDirectories](https://github.com/genXdev/GenXdev.AI/tree/main#add-imagedirectories) | addimgdir | Adds directories to the configured image directories for GenXdev.AI operations. |
| [Approve-NewTextFileContent](https://github.com/genXdev/GenXdev.AI/tree/main#approve-newtextfilecontent) | &nbsp; | Interactive file content comparison and approval using WinMerge. |
| [Compare-ImageFaces](https://github.com/genXdev/GenXdev.AI/tree/main#compare-imagefaces) | comparefaces | &nbsp; |
| [Convert-DotNetTypeToLLMType](https://github.com/genXdev/GenXdev.AI/tree/main#convert-dotnettypetollmtype) | &nbsp; | Converts .NET type names to LLM (Language Model) type names. |
| [ConvertComfyImageFormat](https://github.com/genXdev/GenXdev.AI/tree/main#convertcomfyimageformat) | &nbsp; | Converts image file format while preserving maximum quality. |
| [ConvertFrom-CorporateSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertfrom-corporatespeak) | uncorporatize | &nbsp; |
| [ConvertFrom-DiplomaticSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertfrom-diplomaticspeak) | undiplomatize | &nbsp; |
| [ConvertTo-CorporateSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertto-corporatespeak) | corporatize | &nbsp; |
| [ConvertTo-DiplomaticSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertto-diplomaticspeak) | diplomatize | &nbsp; |
| [ConvertTo-LMStudioFunctionDefinition](https://github.com/genXdev/GenXdev.AI/tree/main#convertto-lmstudiofunctiondefinition) | &nbsp; | &nbsp; |
| [CreateComfySDXLWorkflow](https://github.com/genXdev/GenXdev.AI/tree/main#createcomfysdxlworkflow) | &nbsp; | Creates comprehensive ComfyUI SDXL workflow configuration supporting all parameters |
| [CreateComfyUniversalWorkflow](https://github.com/genXdev/GenXdev.AI/tree/main#createcomfyuniversalworkflow) | &nbsp; | &nbsp; |
| [DownloadComfyResults](https://github.com/genXdev/GenXdev.AI/tree/main#downloadcomfyresults) | &nbsp; | Downloads generated results from ComfyUI server with file information |
| [EnsureComfyUI](https://github.com/genXdev/GenXdev.AI/tree/main#ensurecomfyui) | &nbsp; | Ensures ComfyUI is installed and running with optional window positioning. |
| [EnsureComfyUIModel](https://github.com/genXdev/GenXdev.AI/tree/main#ensurecomfyuimodel) | &nbsp; | Ensures specified ComfyUI models are available locally with automatic download |
| [EnsureDeepStack](https://github.com/genXdev/GenXdev.AI/tree/main#ensuredeepstack) | &nbsp; | &nbsp; |
| [EnsureGithubCLIInstalled](https://github.com/genXdev/GenXdev.AI/tree/main#ensuregithubcliinstalled) | &nbsp; | Ensures GitHub CLI is properly installed and configured on the system. |
| [EnsureHuggingFace](https://github.com/genXdev/GenXdev.AI/tree/main#ensurehuggingface) | &nbsp; | &nbsp; |
| [EnsureLMStudio](https://github.com/genXdev/GenXdev.AI/tree/main#ensurelmstudio) | &nbsp; | &nbsp; |
| [EnsurePaintNet](https://github.com/genXdev/GenXdev.AI/tree/main#ensurepaintnet) | &nbsp; | Ensures Paint.NET is properly installed and accessible on the system. |
| [EnsurePip](https://github.com/genXdev/GenXdev.AI/tree/main#ensurepip) | &nbsp; | Ensures pip is installed and functional for the specified Python installation. |
| [EnsurePython](https://github.com/genXdev/GenXdev.AI/tree/main#ensurepython) | &nbsp; | &nbsp; |
| [EnsureWinMergeInstalled](https://github.com/genXdev/GenXdev.AI/tree/main#ensurewinmergeinstalled) | &nbsp; | Ensures WinMerge is installed and available for file comparison operations. |
| [Export-ImageIndex](https://github.com/genXdev/GenXdev.AI/tree/main#export-imageindex) | indeximages | &nbsp; |
| [Find-Image](https://github.com/genXdev/GenXdev.AI/tree/main#find-image) | findimages, li | &nbsp; |
| [Find-IndexedImage](https://github.com/genXdev/GenXdev.AI/tree/main#find-indexedimage) | findindexedimages, lii | &nbsp; |
| [GenerateMasonryLayoutHtml](https://github.com/genXdev/GenXdev.AI/tree/main#generatemasonrylayouthtml) | &nbsp; | Generates a responsive masonry layout HTML gallery from image data. |
| [Get-AIDefaultLLMSettings](https://github.com/genXdev/GenXdev.AI/tree/main#get-aidefaultllmsettings) | &nbsp; | &nbsp; |
| [Get-AIImageCollection](https://github.com/genXdev/GenXdev.AI/tree/main#get-aiimagecollection) | getimgdirs | &nbsp; |
| [Get-AIKnownFacesRootpath](https://github.com/genXdev/GenXdev.AI/tree/main#get-aiknownfacesrootpath) | &nbsp; | Gets the configured directory for face image files used in GenXdev.AI operations. |
| [Get-AILLMSettings](https://github.com/genXdev/GenXdev.AI/tree/main#get-aillmsettings) | &nbsp; | &nbsp; |
| [Get-AIMetaLanguage](https://github.com/genXdev/GenXdev.AI/tree/main#get-aimetalanguage) | getimgmetalang | Gets the configured default language for image metadata operations. |
| [Get-ComfyUIModelPath](https://github.com/genXdev/GenXdev.AI/tree/main#get-comfyuimodelpath) | &nbsp; | Gets the correct ComfyUI models directory path for the current installation |
| [Get-CpuCore](https://github.com/genXdev/GenXdev.AI/tree/main#get-cpucore) | &nbsp; | Calculates and returns the total number of logical CPU cores in the system. |
| [Get-Fallacy](https://github.com/genXdev/GenXdev.AI/tree/main#get-fallacy) | dispicetext | &nbsp; |
| [Get-HasCapableGpu](https://github.com/genXdev/GenXdev.AI/tree/main#get-hascapablegpu) | &nbsp; | Determines if a CUDA-capable GPU with sufficient memory is present. |
| [Get-ImageDetectedFaces](https://github.com/genXdev/GenXdev.AI/tree/main#get-imagedetectedfaces) | &nbsp; | &nbsp; |
| [Get-ImageDetectedObjects](https://github.com/genXdev/GenXdev.AI/tree/main#get-imagedetectedobjects) | &nbsp; | Detects and classifies objects in an uploaded image using DeepStack. |
| [Get-ImageDetectedScenes](https://github.com/genXdev/GenXdev.AI/tree/main#get-imagedetectedscenes) | &nbsp; | &nbsp; |
| [Get-ImageIndexPath](https://github.com/genXdev/GenXdev.AI/tree/main#get-imageindexpath) | &nbsp; | Returns the path to the image database, initializing or rebuilding it if needed. |
| [Get-ImageIndexStats](https://github.com/genXdev/GenXdev.AI/tree/main#get-imageindexstats) | getimagedbstats, gids | &nbsp; |
| [Get-LMStudioLoadedModelList](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudioloadedmodellist) | &nbsp; | Retrieves the list of currently loaded models from LM Studio. |
| [Get-LMStudioModelList](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiomodellist) | &nbsp; | Retrieves a list of installed LM Studio models. |
| [Get-LMStudioPaths](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiopaths) | &nbsp; | Retrieves file paths for LM Studio executables. |
| [Get-LMStudioTextEmbedding](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiotextembedding) | &nbsp; | Gets text embeddings from LM Studio model. |
| [Get-LMStudioWindow](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiowindow) | lmstudiowindow, setlmstudiowindow | Gets a window helper for the LM Studio application. |
| [Get-NumberOfCpuCores](https://github.com/genXdev/GenXdev.AI/tree/main#get-numberofcpucores) | &nbsp; | Calculates and returns the total number of logical CPU cores in the system. |
| [Get-RegisteredFaces](https://github.com/genXdev/GenXdev.AI/tree/main#get-registeredfaces) | &nbsp; | &nbsp; |
| [Get-ScriptExecutionErrorFixPrompt](https://github.com/genXdev/GenXdev.AI/tree/main#get-scriptexecutionerrorfixprompt) | getfixprompt | &nbsp; |
| [Get-SimularMovieTitles](https://github.com/genXdev/GenXdev.AI/tree/main#get-simularmovietitles) | &nbsp; | Finds similar movie titles based on common properties. |
| [Get-TextTranslation](https://github.com/genXdev/GenXdev.AI/tree/main#get-texttranslation) | translate | &nbsp; |
| [Get-VectorSimilarity](https://github.com/genXdev/GenXdev.AI/tree/main#get-vectorsimilarity) | &nbsp; | Calculates the cosine similarity between two vectors, returning a value between 0 and 1. |
| [Initialize-LMStudioModel](https://github.com/genXdev/GenXdev.AI/tree/main#initialize-lmstudiomodel) | initlmstudio | &nbsp; |
| [Install-LMStudioApplication](https://github.com/genXdev/GenXdev.AI/tree/main#install-lmstudioapplication) | &nbsp; | Installs LM Studio application using WinGet package manager. |
| [Invoke-AIPowershellCommand](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-aipowershellcommand) | hint | &nbsp; |
| [Invoke-ComfyUIImageGeneration](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-comfyuiimagegeneration) | generateimage | &nbsp; |
| [Invoke-CommandFromToolCall](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-commandfromtoolcall) | &nbsp; | &nbsp; |
| [Invoke-HuggingFaceCli](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-huggingfacecli) | &nbsp; | &nbsp; |
| [Invoke-ImageEnhancement](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imageenhancement) | enhanceimage | &nbsp; |
| [Invoke-ImageFacesUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagefacesupdate) | imagepeopledetection | &nbsp; |
| [Invoke-ImageKeywordUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagekeywordupdate) | imagekeywordgeneration | &nbsp; |
| [Invoke-ImageMetadataUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagemetadataupdate) | imagepropdetection | &nbsp; |
| [Invoke-ImageObjectsUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imageobjectsupdate) | imageobjectdetection | &nbsp; |
| [Invoke-ImageScenesUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagescenesupdate) | imagescenedetection | &nbsp; |
| [Invoke-LLMBooleanEvaluation](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmbooleanevaluation) | equalstrue | &nbsp; |
| [Invoke-LLMQuery](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmquery) | llm, qllm | &nbsp; |
| [Invoke-LLMStringListEvaluation](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmstringlistevaluation) | getlist, getstring | &nbsp; |
| [Invoke-LLMTextTransformation](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmtexttransformation) | spellcheck | &nbsp; |
| [Invoke-QueryImageContent](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-queryimagecontent) | &nbsp; | &nbsp; |
| [Invoke-WinMerge](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-winmerge) | &nbsp; | Launches WinMerge to compare two files side by side. |
| [New-LLMAudioChat](https://github.com/genXdev/GenXdev.AI/tree/main#new-llmaudiochat) | llmaudiochat | &nbsp; |
| [New-LLMTextChat](https://github.com/genXdev/GenXdev.AI/tree/main#new-llmtextchat) | llmchat | &nbsp; |
| [QueueComfyWorkflow](https://github.com/genXdev/GenXdev.AI/tree/main#queuecomfyworkflow) | &nbsp; | &nbsp; |
| [Register-AllFaces](https://github.com/genXdev/GenXdev.AI/tree/main#register-allfaces) | UpdateFaces | &nbsp; |
| [Register-Face](https://github.com/genXdev/GenXdev.AI/tree/main#register-face) | &nbsp; | &nbsp; |
| [Remove-ImageDirectories](https://github.com/genXdev/GenXdev.AI/tree/main#remove-imagedirectories) | removeimgdir | &nbsp; |
| [Remove-ImageMetaData](https://github.com/genXdev/GenXdev.AI/tree/main#remove-imagemetadata) | removeimagedata | &nbsp; |
| [ResizeComfyInputImage](https://github.com/genXdev/GenXdev.AI/tree/main#resizecomfyinputimage) | &nbsp; | &nbsp; |
| [Save-FoundImageFaces](https://github.com/genXdev/GenXdev.AI/tree/main#save-foundimagefaces) | saveimagefaces | &nbsp; |
| [Save-FoundImageObjects](https://github.com/genXdev/GenXdev.AI/tree/main#save-foundimageobjects) | saveimageObjects | &nbsp; |
| [Save-Transcriptions](https://github.com/genXdev/GenXdev.AI/tree/main#save-transcriptions) | &nbsp; | &nbsp; |
| [Set-AIImageCollection](https://github.com/genXdev/GenXdev.AI/tree/main#set-aiimagecollection) | &nbsp; | &nbsp; |
| [Set-AIKnownFacesRootpath](https://github.com/genXdev/GenXdev.AI/tree/main#set-aiknownfacesrootpath) | &nbsp; | Sets the directory for face image files used in GenXdev.AI operations. |
| [Set-AILLMSettings](https://github.com/genXdev/GenXdev.AI/tree/main#set-aillmsettings) | &nbsp; | &nbsp; |
| [Set-AIMetaLanguage](https://github.com/genXdev/GenXdev.AI/tree/main#set-aimetalanguage) | &nbsp; | Sets the default language and optionally the image directories for GenXdev.AI image metadata operations. |
| [Set-ComfyUIBackgroundImage](https://github.com/genXdev/GenXdev.AI/tree/main#set-comfyuibackgroundimage) | &nbsp; | Sets or clears the background image for ComfyUI's canvas interface |
| [Set-ComfyUIModelPath](https://github.com/genXdev/GenXdev.AI/tree/main#set-comfyuimodelpath) | &nbsp; | &nbsp; |
| [Set-GenXdevAICommandNotFoundAction](https://github.com/genXdev/GenXdev.AI/tree/main#set-genxdevaicommandnotfoundaction) | &nbsp; | &nbsp; |
| [Set-ImageIndexPath](https://github.com/genXdev/GenXdev.AI/tree/main#set-imageindexpath) | &nbsp; | Sets the default database file path for image operations in GenXdev.AI. |
| [Set-WindowsWallpaperEx](https://github.com/genXdev/GenXdev.AI/tree/main#set-windowswallpaperex) | nextwallpaper | &nbsp; |
| [SetComfyUIProcessPriority](https://github.com/genXdev/GenXdev.AI/tree/main#setcomfyuiprocesspriority) | &nbsp; | &nbsp; |
| [Show-FoundImagesInBrowser](https://github.com/genXdev/GenXdev.AI/tree/main#show-foundimagesinbrowser) | showfoundimages | &nbsp; |
| [Show-GenXdevScriptErrorFixInIde](https://github.com/genXdev/GenXdev.AI/tree/main#show-genxdevscripterrorfixinide) | letsfixthis | &nbsp; |
| [Start-AudioTranscription](https://github.com/genXdev/GenXdev.AI/tree/main#start-audiotranscription) | transcribe, transcribefile | &nbsp; |
| [Start-GenXdevMCPServer](https://github.com/genXdev/GenXdev.AI/tree/main#start-genxdevmcpserver) | &nbsp; | &nbsp; |
| [Start-LMStudioApplication](https://github.com/genXdev/GenXdev.AI/tree/main#start-lmstudioapplication) | &nbsp; | Starts the LM Studio application if it's not already running. |
| [Stop-ComfyUI](https://github.com/genXdev/GenXdev.AI/tree/main#stop-comfyui) | &nbsp; | Terminates all running ComfyUI processes and releases associated resources. |
| [Test-ComfyUIQueueEmpty](https://github.com/genXdev/GenXdev.AI/tree/main#test-comfyuiqueueempty) | &nbsp; | Checks if the ComfyUI processing queue is empty |
| [Test-DeepLinkImageFile](https://github.com/genXdev/GenXdev.AI/tree/main#test-deeplinkimagefile) | &nbsp; | Tests if the specified file path is a valid image file with a supported format. |
| [Test-LMStudioInstallation](https://github.com/genXdev/GenXdev.AI/tree/main#test-lmstudioinstallation) | &nbsp; | Tests if LMStudio is installed and accessible on the system. |
| [Test-LMStudioProcess](https://github.com/genXdev/GenXdev.AI/tree/main#test-lmstudioprocess) | &nbsp; | Tests if LM Studio process is running and configures its window state. |
| [Unregister-AllFaces](https://github.com/genXdev/GenXdev.AI/tree/main#unregister-allfaces) | &nbsp; | Removes all registered faces from the DeepStack face recognition system. |
| [Unregister-Face](https://github.com/genXdev/GenXdev.AI/tree/main#unregister-face) | &nbsp; | Deletes a registered face by its identifier from DeepStack. |
| [Update-AllImageMetaData](https://github.com/genXdev/GenXdev.AI/tree/main#update-allimagemetadata) | updateallimages | &nbsp; |
| [UploadComfyImage](https://github.com/genXdev/GenXdev.AI/tree/main#uploadcomfyimage) | &nbsp; | &nbsp; |
| [WaitForComfyCompletion](https://github.com/genXdev/GenXdev.AI/tree/main#waitforcomfycompletion) | &nbsp; | &nbsp; |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.AI/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.AI.DeepStack

**A Windows PowerShell module for local AI related operations**

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [Add-EmoticonsToText](https://github.com/genXdev/GenXdev.AI/tree/main#add-emoticonstotext) | emojify | &nbsp; |
| [Add-GenXdevMCPServerToLMStudio](https://github.com/genXdev/GenXdev.AI/tree/main#add-genxdevmcpservertolmstudio) | &nbsp; | Adds the GenXdev MCP server to LM Studio using a deeplink configuration. |
| [Add-ImageDirectories](https://github.com/genXdev/GenXdev.AI/tree/main#add-imagedirectories) | addimgdir | Adds directories to the configured image directories for GenXdev.AI operations. |
| [Approve-NewTextFileContent](https://github.com/genXdev/GenXdev.AI/tree/main#approve-newtextfilecontent) | &nbsp; | Interactive file content comparison and approval using WinMerge. |
| [Compare-ImageFaces](https://github.com/genXdev/GenXdev.AI/tree/main#compare-imagefaces) | comparefaces | &nbsp; |
| [Convert-DotNetTypeToLLMType](https://github.com/genXdev/GenXdev.AI/tree/main#convert-dotnettypetollmtype) | &nbsp; | Converts .NET type names to LLM (Language Model) type names. |
| [ConvertComfyImageFormat](https://github.com/genXdev/GenXdev.AI/tree/main#convertcomfyimageformat) | &nbsp; | Converts image file format while preserving maximum quality. |
| [ConvertFrom-CorporateSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertfrom-corporatespeak) | uncorporatize | &nbsp; |
| [ConvertFrom-DiplomaticSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertfrom-diplomaticspeak) | undiplomatize | &nbsp; |
| [ConvertTo-CorporateSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertto-corporatespeak) | corporatize | &nbsp; |
| [ConvertTo-DiplomaticSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertto-diplomaticspeak) | diplomatize | &nbsp; |
| [ConvertTo-LMStudioFunctionDefinition](https://github.com/genXdev/GenXdev.AI/tree/main#convertto-lmstudiofunctiondefinition) | &nbsp; | &nbsp; |
| [CreateComfySDXLWorkflow](https://github.com/genXdev/GenXdev.AI/tree/main#createcomfysdxlworkflow) | &nbsp; | Creates comprehensive ComfyUI SDXL workflow configuration supporting all parameters |
| [CreateComfyUniversalWorkflow](https://github.com/genXdev/GenXdev.AI/tree/main#createcomfyuniversalworkflow) | &nbsp; | &nbsp; |
| [DownloadComfyResults](https://github.com/genXdev/GenXdev.AI/tree/main#downloadcomfyresults) | &nbsp; | Downloads generated results from ComfyUI server with file information |
| [EnsureComfyUI](https://github.com/genXdev/GenXdev.AI/tree/main#ensurecomfyui) | &nbsp; | Ensures ComfyUI is installed and running with optional window positioning. |
| [EnsureComfyUIModel](https://github.com/genXdev/GenXdev.AI/tree/main#ensurecomfyuimodel) | &nbsp; | Ensures specified ComfyUI models are available locally with automatic download |
| [EnsureDeepStack](https://github.com/genXdev/GenXdev.AI/tree/main#ensuredeepstack) | &nbsp; | &nbsp; |
| [EnsureGithubCLIInstalled](https://github.com/genXdev/GenXdev.AI/tree/main#ensuregithubcliinstalled) | &nbsp; | Ensures GitHub CLI is properly installed and configured on the system. |
| [EnsureHuggingFace](https://github.com/genXdev/GenXdev.AI/tree/main#ensurehuggingface) | &nbsp; | &nbsp; |
| [EnsureLMStudio](https://github.com/genXdev/GenXdev.AI/tree/main#ensurelmstudio) | &nbsp; | &nbsp; |
| [EnsurePaintNet](https://github.com/genXdev/GenXdev.AI/tree/main#ensurepaintnet) | &nbsp; | Ensures Paint.NET is properly installed and accessible on the system. |
| [EnsurePip](https://github.com/genXdev/GenXdev.AI/tree/main#ensurepip) | &nbsp; | Ensures pip is installed and functional for the specified Python installation. |
| [EnsurePython](https://github.com/genXdev/GenXdev.AI/tree/main#ensurepython) | &nbsp; | &nbsp; |
| [EnsureWinMergeInstalled](https://github.com/genXdev/GenXdev.AI/tree/main#ensurewinmergeinstalled) | &nbsp; | Ensures WinMerge is installed and available for file comparison operations. |
| [Export-ImageIndex](https://github.com/genXdev/GenXdev.AI/tree/main#export-imageindex) | indeximages | &nbsp; |
| [Find-Image](https://github.com/genXdev/GenXdev.AI/tree/main#find-image) | findimages, li | &nbsp; |
| [Find-IndexedImage](https://github.com/genXdev/GenXdev.AI/tree/main#find-indexedimage) | findindexedimages, lii | &nbsp; |
| [GenerateMasonryLayoutHtml](https://github.com/genXdev/GenXdev.AI/tree/main#generatemasonrylayouthtml) | &nbsp; | Generates a responsive masonry layout HTML gallery from image data. |
| [Get-AIDefaultLLMSettings](https://github.com/genXdev/GenXdev.AI/tree/main#get-aidefaultllmsettings) | &nbsp; | &nbsp; |
| [Get-AIImageCollection](https://github.com/genXdev/GenXdev.AI/tree/main#get-aiimagecollection) | getimgdirs | &nbsp; |
| [Get-AIKnownFacesRootpath](https://github.com/genXdev/GenXdev.AI/tree/main#get-aiknownfacesrootpath) | &nbsp; | Gets the configured directory for face image files used in GenXdev.AI operations. |
| [Get-AILLMSettings](https://github.com/genXdev/GenXdev.AI/tree/main#get-aillmsettings) | &nbsp; | &nbsp; |
| [Get-AIMetaLanguage](https://github.com/genXdev/GenXdev.AI/tree/main#get-aimetalanguage) | getimgmetalang | Gets the configured default language for image metadata operations. |
| [Get-ComfyUIModelPath](https://github.com/genXdev/GenXdev.AI/tree/main#get-comfyuimodelpath) | &nbsp; | Gets the correct ComfyUI models directory path for the current installation |
| [Get-CpuCore](https://github.com/genXdev/GenXdev.AI/tree/main#get-cpucore) | &nbsp; | Calculates and returns the total number of logical CPU cores in the system. |
| [Get-Fallacy](https://github.com/genXdev/GenXdev.AI/tree/main#get-fallacy) | dispicetext | &nbsp; |
| [Get-HasCapableGpu](https://github.com/genXdev/GenXdev.AI/tree/main#get-hascapablegpu) | &nbsp; | Determines if a CUDA-capable GPU with sufficient memory is present. |
| [Get-ImageDetectedFaces](https://github.com/genXdev/GenXdev.AI/tree/main#get-imagedetectedfaces) | &nbsp; | &nbsp; |
| [Get-ImageDetectedObjects](https://github.com/genXdev/GenXdev.AI/tree/main#get-imagedetectedobjects) | &nbsp; | Detects and classifies objects in an uploaded image using DeepStack. |
| [Get-ImageDetectedScenes](https://github.com/genXdev/GenXdev.AI/tree/main#get-imagedetectedscenes) | &nbsp; | &nbsp; |
| [Get-ImageIndexPath](https://github.com/genXdev/GenXdev.AI/tree/main#get-imageindexpath) | &nbsp; | Returns the path to the image database, initializing or rebuilding it if needed. |
| [Get-ImageIndexStats](https://github.com/genXdev/GenXdev.AI/tree/main#get-imageindexstats) | getimagedbstats, gids | &nbsp; |
| [Get-LMStudioLoadedModelList](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudioloadedmodellist) | &nbsp; | Retrieves the list of currently loaded models from LM Studio. |
| [Get-LMStudioModelList](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiomodellist) | &nbsp; | Retrieves a list of installed LM Studio models. |
| [Get-LMStudioPaths](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiopaths) | &nbsp; | Retrieves file paths for LM Studio executables. |
| [Get-LMStudioTextEmbedding](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiotextembedding) | &nbsp; | Gets text embeddings from LM Studio model. |
| [Get-LMStudioWindow](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiowindow) | lmstudiowindow, setlmstudiowindow | Gets a window helper for the LM Studio application. |
| [Get-NumberOfCpuCores](https://github.com/genXdev/GenXdev.AI/tree/main#get-numberofcpucores) | &nbsp; | Calculates and returns the total number of logical CPU cores in the system. |
| [Get-RegisteredFaces](https://github.com/genXdev/GenXdev.AI/tree/main#get-registeredfaces) | &nbsp; | &nbsp; |
| [Get-ScriptExecutionErrorFixPrompt](https://github.com/genXdev/GenXdev.AI/tree/main#get-scriptexecutionerrorfixprompt) | getfixprompt | &nbsp; |
| [Get-SimularMovieTitles](https://github.com/genXdev/GenXdev.AI/tree/main#get-simularmovietitles) | &nbsp; | Finds similar movie titles based on common properties. |
| [Get-TextTranslation](https://github.com/genXdev/GenXdev.AI/tree/main#get-texttranslation) | translate | &nbsp; |
| [Get-VectorSimilarity](https://github.com/genXdev/GenXdev.AI/tree/main#get-vectorsimilarity) | &nbsp; | Calculates the cosine similarity between two vectors, returning a value between 0 and 1. |
| [Initialize-LMStudioModel](https://github.com/genXdev/GenXdev.AI/tree/main#initialize-lmstudiomodel) | initlmstudio | &nbsp; |
| [Install-LMStudioApplication](https://github.com/genXdev/GenXdev.AI/tree/main#install-lmstudioapplication) | &nbsp; | Installs LM Studio application using WinGet package manager. |
| [Invoke-AIPowershellCommand](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-aipowershellcommand) | hint | &nbsp; |
| [Invoke-ComfyUIImageGeneration](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-comfyuiimagegeneration) | generateimage | &nbsp; |
| [Invoke-CommandFromToolCall](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-commandfromtoolcall) | &nbsp; | &nbsp; |
| [Invoke-HuggingFaceCli](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-huggingfacecli) | &nbsp; | &nbsp; |
| [Invoke-ImageEnhancement](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imageenhancement) | enhanceimage | &nbsp; |
| [Invoke-ImageFacesUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagefacesupdate) | imagepeopledetection | &nbsp; |
| [Invoke-ImageKeywordUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagekeywordupdate) | imagekeywordgeneration | &nbsp; |
| [Invoke-ImageMetadataUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagemetadataupdate) | imagepropdetection | &nbsp; |
| [Invoke-ImageObjectsUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imageobjectsupdate) | imageobjectdetection | &nbsp; |
| [Invoke-ImageScenesUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagescenesupdate) | imagescenedetection | &nbsp; |
| [Invoke-LLMBooleanEvaluation](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmbooleanevaluation) | equalstrue | &nbsp; |
| [Invoke-LLMQuery](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmquery) | llm, qllm | &nbsp; |
| [Invoke-LLMStringListEvaluation](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmstringlistevaluation) | getlist, getstring | &nbsp; |
| [Invoke-LLMTextTransformation](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmtexttransformation) | spellcheck | &nbsp; |
| [Invoke-QueryImageContent](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-queryimagecontent) | &nbsp; | &nbsp; |
| [Invoke-WinMerge](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-winmerge) | &nbsp; | Launches WinMerge to compare two files side by side. |
| [New-LLMAudioChat](https://github.com/genXdev/GenXdev.AI/tree/main#new-llmaudiochat) | llmaudiochat | &nbsp; |
| [New-LLMTextChat](https://github.com/genXdev/GenXdev.AI/tree/main#new-llmtextchat) | llmchat | &nbsp; |
| [QueueComfyWorkflow](https://github.com/genXdev/GenXdev.AI/tree/main#queuecomfyworkflow) | &nbsp; | &nbsp; |
| [Register-AllFaces](https://github.com/genXdev/GenXdev.AI/tree/main#register-allfaces) | UpdateFaces | &nbsp; |
| [Register-Face](https://github.com/genXdev/GenXdev.AI/tree/main#register-face) | &nbsp; | &nbsp; |
| [Remove-ImageDirectories](https://github.com/genXdev/GenXdev.AI/tree/main#remove-imagedirectories) | removeimgdir | &nbsp; |
| [Remove-ImageMetaData](https://github.com/genXdev/GenXdev.AI/tree/main#remove-imagemetadata) | removeimagedata | &nbsp; |
| [ResizeComfyInputImage](https://github.com/genXdev/GenXdev.AI/tree/main#resizecomfyinputimage) | &nbsp; | &nbsp; |
| [Save-FoundImageFaces](https://github.com/genXdev/GenXdev.AI/tree/main#save-foundimagefaces) | saveimagefaces | &nbsp; |
| [Save-FoundImageObjects](https://github.com/genXdev/GenXdev.AI/tree/main#save-foundimageobjects) | saveimageObjects | &nbsp; |
| [Save-Transcriptions](https://github.com/genXdev/GenXdev.AI/tree/main#save-transcriptions) | &nbsp; | &nbsp; |
| [Set-AIImageCollection](https://github.com/genXdev/GenXdev.AI/tree/main#set-aiimagecollection) | &nbsp; | &nbsp; |
| [Set-AIKnownFacesRootpath](https://github.com/genXdev/GenXdev.AI/tree/main#set-aiknownfacesrootpath) | &nbsp; | Sets the directory for face image files used in GenXdev.AI operations. |
| [Set-AILLMSettings](https://github.com/genXdev/GenXdev.AI/tree/main#set-aillmsettings) | &nbsp; | &nbsp; |
| [Set-AIMetaLanguage](https://github.com/genXdev/GenXdev.AI/tree/main#set-aimetalanguage) | &nbsp; | Sets the default language and optionally the image directories for GenXdev.AI image metadata operations. |
| [Set-ComfyUIBackgroundImage](https://github.com/genXdev/GenXdev.AI/tree/main#set-comfyuibackgroundimage) | &nbsp; | Sets or clears the background image for ComfyUI's canvas interface |
| [Set-ComfyUIModelPath](https://github.com/genXdev/GenXdev.AI/tree/main#set-comfyuimodelpath) | &nbsp; | &nbsp; |
| [Set-GenXdevAICommandNotFoundAction](https://github.com/genXdev/GenXdev.AI/tree/main#set-genxdevaicommandnotfoundaction) | &nbsp; | &nbsp; |
| [Set-ImageIndexPath](https://github.com/genXdev/GenXdev.AI/tree/main#set-imageindexpath) | &nbsp; | Sets the default database file path for image operations in GenXdev.AI. |
| [Set-WindowsWallpaperEx](https://github.com/genXdev/GenXdev.AI/tree/main#set-windowswallpaperex) | nextwallpaper | &nbsp; |
| [SetComfyUIProcessPriority](https://github.com/genXdev/GenXdev.AI/tree/main#setcomfyuiprocesspriority) | &nbsp; | &nbsp; |
| [Show-FoundImagesInBrowser](https://github.com/genXdev/GenXdev.AI/tree/main#show-foundimagesinbrowser) | showfoundimages | &nbsp; |
| [Show-GenXdevScriptErrorFixInIde](https://github.com/genXdev/GenXdev.AI/tree/main#show-genxdevscripterrorfixinide) | letsfixthis | &nbsp; |
| [Start-AudioTranscription](https://github.com/genXdev/GenXdev.AI/tree/main#start-audiotranscription) | transcribe, transcribefile | &nbsp; |
| [Start-GenXdevMCPServer](https://github.com/genXdev/GenXdev.AI/tree/main#start-genxdevmcpserver) | &nbsp; | &nbsp; |
| [Start-LMStudioApplication](https://github.com/genXdev/GenXdev.AI/tree/main#start-lmstudioapplication) | &nbsp; | Starts the LM Studio application if it's not already running. |
| [Stop-ComfyUI](https://github.com/genXdev/GenXdev.AI/tree/main#stop-comfyui) | &nbsp; | Terminates all running ComfyUI processes and releases associated resources. |
| [Test-ComfyUIQueueEmpty](https://github.com/genXdev/GenXdev.AI/tree/main#test-comfyuiqueueempty) | &nbsp; | Checks if the ComfyUI processing queue is empty |
| [Test-DeepLinkImageFile](https://github.com/genXdev/GenXdev.AI/tree/main#test-deeplinkimagefile) | &nbsp; | Tests if the specified file path is a valid image file with a supported format. |
| [Test-LMStudioInstallation](https://github.com/genXdev/GenXdev.AI/tree/main#test-lmstudioinstallation) | &nbsp; | Tests if LMStudio is installed and accessible on the system. |
| [Test-LMStudioProcess](https://github.com/genXdev/GenXdev.AI/tree/main#test-lmstudioprocess) | &nbsp; | Tests if LM Studio process is running and configures its window state. |
| [Unregister-AllFaces](https://github.com/genXdev/GenXdev.AI/tree/main#unregister-allfaces) | &nbsp; | Removes all registered faces from the DeepStack face recognition system. |
| [Unregister-Face](https://github.com/genXdev/GenXdev.AI/tree/main#unregister-face) | &nbsp; | Deletes a registered face by its identifier from DeepStack. |
| [Update-AllImageMetaData](https://github.com/genXdev/GenXdev.AI/tree/main#update-allimagemetadata) | updateallimages | &nbsp; |
| [UploadComfyImage](https://github.com/genXdev/GenXdev.AI/tree/main#uploadcomfyimage) | &nbsp; | &nbsp; |
| [WaitForComfyCompletion](https://github.com/genXdev/GenXdev.AI/tree/main#waitforcomfycompletion) | &nbsp; | &nbsp; |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.AI/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.AI.LMStudio

**A Windows PowerShell module for local AI related operations**

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [Add-EmoticonsToText](https://github.com/genXdev/GenXdev.AI/tree/main#add-emoticonstotext) | emojify | &nbsp; |
| [Add-GenXdevMCPServerToLMStudio](https://github.com/genXdev/GenXdev.AI/tree/main#add-genxdevmcpservertolmstudio) | &nbsp; | Adds the GenXdev MCP server to LM Studio using a deeplink configuration. |
| [Add-ImageDirectories](https://github.com/genXdev/GenXdev.AI/tree/main#add-imagedirectories) | addimgdir | Adds directories to the configured image directories for GenXdev.AI operations. |
| [Approve-NewTextFileContent](https://github.com/genXdev/GenXdev.AI/tree/main#approve-newtextfilecontent) | &nbsp; | Interactive file content comparison and approval using WinMerge. |
| [Compare-ImageFaces](https://github.com/genXdev/GenXdev.AI/tree/main#compare-imagefaces) | comparefaces | &nbsp; |
| [Convert-DotNetTypeToLLMType](https://github.com/genXdev/GenXdev.AI/tree/main#convert-dotnettypetollmtype) | &nbsp; | Converts .NET type names to LLM (Language Model) type names. |
| [ConvertComfyImageFormat](https://github.com/genXdev/GenXdev.AI/tree/main#convertcomfyimageformat) | &nbsp; | Converts image file format while preserving maximum quality. |
| [ConvertFrom-CorporateSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertfrom-corporatespeak) | uncorporatize | &nbsp; |
| [ConvertFrom-DiplomaticSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertfrom-diplomaticspeak) | undiplomatize | &nbsp; |
| [ConvertTo-CorporateSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertto-corporatespeak) | corporatize | &nbsp; |
| [ConvertTo-DiplomaticSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertto-diplomaticspeak) | diplomatize | &nbsp; |
| [ConvertTo-LMStudioFunctionDefinition](https://github.com/genXdev/GenXdev.AI/tree/main#convertto-lmstudiofunctiondefinition) | &nbsp; | &nbsp; |
| [CreateComfySDXLWorkflow](https://github.com/genXdev/GenXdev.AI/tree/main#createcomfysdxlworkflow) | &nbsp; | Creates comprehensive ComfyUI SDXL workflow configuration supporting all parameters |
| [CreateComfyUniversalWorkflow](https://github.com/genXdev/GenXdev.AI/tree/main#createcomfyuniversalworkflow) | &nbsp; | &nbsp; |
| [DownloadComfyResults](https://github.com/genXdev/GenXdev.AI/tree/main#downloadcomfyresults) | &nbsp; | Downloads generated results from ComfyUI server with file information |
| [EnsureComfyUI](https://github.com/genXdev/GenXdev.AI/tree/main#ensurecomfyui) | &nbsp; | Ensures ComfyUI is installed and running with optional window positioning. |
| [EnsureComfyUIModel](https://github.com/genXdev/GenXdev.AI/tree/main#ensurecomfyuimodel) | &nbsp; | Ensures specified ComfyUI models are available locally with automatic download |
| [EnsureDeepStack](https://github.com/genXdev/GenXdev.AI/tree/main#ensuredeepstack) | &nbsp; | &nbsp; |
| [EnsureGithubCLIInstalled](https://github.com/genXdev/GenXdev.AI/tree/main#ensuregithubcliinstalled) | &nbsp; | Ensures GitHub CLI is properly installed and configured on the system. |
| [EnsureHuggingFace](https://github.com/genXdev/GenXdev.AI/tree/main#ensurehuggingface) | &nbsp; | &nbsp; |
| [EnsureLMStudio](https://github.com/genXdev/GenXdev.AI/tree/main#ensurelmstudio) | &nbsp; | &nbsp; |
| [EnsurePaintNet](https://github.com/genXdev/GenXdev.AI/tree/main#ensurepaintnet) | &nbsp; | Ensures Paint.NET is properly installed and accessible on the system. |
| [EnsurePip](https://github.com/genXdev/GenXdev.AI/tree/main#ensurepip) | &nbsp; | Ensures pip is installed and functional for the specified Python installation. |
| [EnsurePython](https://github.com/genXdev/GenXdev.AI/tree/main#ensurepython) | &nbsp; | &nbsp; |
| [EnsureWinMergeInstalled](https://github.com/genXdev/GenXdev.AI/tree/main#ensurewinmergeinstalled) | &nbsp; | Ensures WinMerge is installed and available for file comparison operations. |
| [Export-ImageIndex](https://github.com/genXdev/GenXdev.AI/tree/main#export-imageindex) | indeximages | &nbsp; |
| [Find-Image](https://github.com/genXdev/GenXdev.AI/tree/main#find-image) | findimages, li | &nbsp; |
| [Find-IndexedImage](https://github.com/genXdev/GenXdev.AI/tree/main#find-indexedimage) | findindexedimages, lii | &nbsp; |
| [GenerateMasonryLayoutHtml](https://github.com/genXdev/GenXdev.AI/tree/main#generatemasonrylayouthtml) | &nbsp; | Generates a responsive masonry layout HTML gallery from image data. |
| [Get-AIDefaultLLMSettings](https://github.com/genXdev/GenXdev.AI/tree/main#get-aidefaultllmsettings) | &nbsp; | &nbsp; |
| [Get-AIImageCollection](https://github.com/genXdev/GenXdev.AI/tree/main#get-aiimagecollection) | getimgdirs | &nbsp; |
| [Get-AIKnownFacesRootpath](https://github.com/genXdev/GenXdev.AI/tree/main#get-aiknownfacesrootpath) | &nbsp; | Gets the configured directory for face image files used in GenXdev.AI operations. |
| [Get-AILLMSettings](https://github.com/genXdev/GenXdev.AI/tree/main#get-aillmsettings) | &nbsp; | &nbsp; |
| [Get-AIMetaLanguage](https://github.com/genXdev/GenXdev.AI/tree/main#get-aimetalanguage) | getimgmetalang | Gets the configured default language for image metadata operations. |
| [Get-ComfyUIModelPath](https://github.com/genXdev/GenXdev.AI/tree/main#get-comfyuimodelpath) | &nbsp; | Gets the correct ComfyUI models directory path for the current installation |
| [Get-CpuCore](https://github.com/genXdev/GenXdev.AI/tree/main#get-cpucore) | &nbsp; | Calculates and returns the total number of logical CPU cores in the system. |
| [Get-Fallacy](https://github.com/genXdev/GenXdev.AI/tree/main#get-fallacy) | dispicetext | &nbsp; |
| [Get-HasCapableGpu](https://github.com/genXdev/GenXdev.AI/tree/main#get-hascapablegpu) | &nbsp; | Determines if a CUDA-capable GPU with sufficient memory is present. |
| [Get-ImageDetectedFaces](https://github.com/genXdev/GenXdev.AI/tree/main#get-imagedetectedfaces) | &nbsp; | &nbsp; |
| [Get-ImageDetectedObjects](https://github.com/genXdev/GenXdev.AI/tree/main#get-imagedetectedobjects) | &nbsp; | Detects and classifies objects in an uploaded image using DeepStack. |
| [Get-ImageDetectedScenes](https://github.com/genXdev/GenXdev.AI/tree/main#get-imagedetectedscenes) | &nbsp; | &nbsp; |
| [Get-ImageIndexPath](https://github.com/genXdev/GenXdev.AI/tree/main#get-imageindexpath) | &nbsp; | Returns the path to the image database, initializing or rebuilding it if needed. |
| [Get-ImageIndexStats](https://github.com/genXdev/GenXdev.AI/tree/main#get-imageindexstats) | getimagedbstats, gids | &nbsp; |
| [Get-LMStudioLoadedModelList](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudioloadedmodellist) | &nbsp; | Retrieves the list of currently loaded models from LM Studio. |
| [Get-LMStudioModelList](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiomodellist) | &nbsp; | Retrieves a list of installed LM Studio models. |
| [Get-LMStudioPaths](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiopaths) | &nbsp; | Retrieves file paths for LM Studio executables. |
| [Get-LMStudioTextEmbedding](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiotextembedding) | &nbsp; | Gets text embeddings from LM Studio model. |
| [Get-LMStudioWindow](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiowindow) | lmstudiowindow, setlmstudiowindow | Gets a window helper for the LM Studio application. |
| [Get-NumberOfCpuCores](https://github.com/genXdev/GenXdev.AI/tree/main#get-numberofcpucores) | &nbsp; | Calculates and returns the total number of logical CPU cores in the system. |
| [Get-RegisteredFaces](https://github.com/genXdev/GenXdev.AI/tree/main#get-registeredfaces) | &nbsp; | &nbsp; |
| [Get-ScriptExecutionErrorFixPrompt](https://github.com/genXdev/GenXdev.AI/tree/main#get-scriptexecutionerrorfixprompt) | getfixprompt | &nbsp; |
| [Get-SimularMovieTitles](https://github.com/genXdev/GenXdev.AI/tree/main#get-simularmovietitles) | &nbsp; | Finds similar movie titles based on common properties. |
| [Get-TextTranslation](https://github.com/genXdev/GenXdev.AI/tree/main#get-texttranslation) | translate | &nbsp; |
| [Get-VectorSimilarity](https://github.com/genXdev/GenXdev.AI/tree/main#get-vectorsimilarity) | &nbsp; | Calculates the cosine similarity between two vectors, returning a value between 0 and 1. |
| [Initialize-LMStudioModel](https://github.com/genXdev/GenXdev.AI/tree/main#initialize-lmstudiomodel) | initlmstudio | &nbsp; |
| [Install-LMStudioApplication](https://github.com/genXdev/GenXdev.AI/tree/main#install-lmstudioapplication) | &nbsp; | Installs LM Studio application using WinGet package manager. |
| [Invoke-AIPowershellCommand](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-aipowershellcommand) | hint | &nbsp; |
| [Invoke-ComfyUIImageGeneration](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-comfyuiimagegeneration) | generateimage | &nbsp; |
| [Invoke-CommandFromToolCall](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-commandfromtoolcall) | &nbsp; | &nbsp; |
| [Invoke-HuggingFaceCli](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-huggingfacecli) | &nbsp; | &nbsp; |
| [Invoke-ImageEnhancement](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imageenhancement) | enhanceimage | &nbsp; |
| [Invoke-ImageFacesUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagefacesupdate) | imagepeopledetection | &nbsp; |
| [Invoke-ImageKeywordUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagekeywordupdate) | imagekeywordgeneration | &nbsp; |
| [Invoke-ImageMetadataUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagemetadataupdate) | imagepropdetection | &nbsp; |
| [Invoke-ImageObjectsUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imageobjectsupdate) | imageobjectdetection | &nbsp; |
| [Invoke-ImageScenesUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagescenesupdate) | imagescenedetection | &nbsp; |
| [Invoke-LLMBooleanEvaluation](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmbooleanevaluation) | equalstrue | &nbsp; |
| [Invoke-LLMQuery](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmquery) | llm, qllm | &nbsp; |
| [Invoke-LLMStringListEvaluation](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmstringlistevaluation) | getlist, getstring | &nbsp; |
| [Invoke-LLMTextTransformation](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmtexttransformation) | spellcheck | &nbsp; |
| [Invoke-QueryImageContent](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-queryimagecontent) | &nbsp; | &nbsp; |
| [Invoke-WinMerge](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-winmerge) | &nbsp; | Launches WinMerge to compare two files side by side. |
| [New-LLMAudioChat](https://github.com/genXdev/GenXdev.AI/tree/main#new-llmaudiochat) | llmaudiochat | &nbsp; |
| [New-LLMTextChat](https://github.com/genXdev/GenXdev.AI/tree/main#new-llmtextchat) | llmchat | &nbsp; |
| [QueueComfyWorkflow](https://github.com/genXdev/GenXdev.AI/tree/main#queuecomfyworkflow) | &nbsp; | &nbsp; |
| [Register-AllFaces](https://github.com/genXdev/GenXdev.AI/tree/main#register-allfaces) | UpdateFaces | &nbsp; |
| [Register-Face](https://github.com/genXdev/GenXdev.AI/tree/main#register-face) | &nbsp; | &nbsp; |
| [Remove-ImageDirectories](https://github.com/genXdev/GenXdev.AI/tree/main#remove-imagedirectories) | removeimgdir | &nbsp; |
| [Remove-ImageMetaData](https://github.com/genXdev/GenXdev.AI/tree/main#remove-imagemetadata) | removeimagedata | &nbsp; |
| [ResizeComfyInputImage](https://github.com/genXdev/GenXdev.AI/tree/main#resizecomfyinputimage) | &nbsp; | &nbsp; |
| [Save-FoundImageFaces](https://github.com/genXdev/GenXdev.AI/tree/main#save-foundimagefaces) | saveimagefaces | &nbsp; |
| [Save-FoundImageObjects](https://github.com/genXdev/GenXdev.AI/tree/main#save-foundimageobjects) | saveimageObjects | &nbsp; |
| [Save-Transcriptions](https://github.com/genXdev/GenXdev.AI/tree/main#save-transcriptions) | &nbsp; | &nbsp; |
| [Set-AIImageCollection](https://github.com/genXdev/GenXdev.AI/tree/main#set-aiimagecollection) | &nbsp; | &nbsp; |
| [Set-AIKnownFacesRootpath](https://github.com/genXdev/GenXdev.AI/tree/main#set-aiknownfacesrootpath) | &nbsp; | Sets the directory for face image files used in GenXdev.AI operations. |
| [Set-AILLMSettings](https://github.com/genXdev/GenXdev.AI/tree/main#set-aillmsettings) | &nbsp; | &nbsp; |
| [Set-AIMetaLanguage](https://github.com/genXdev/GenXdev.AI/tree/main#set-aimetalanguage) | &nbsp; | Sets the default language and optionally the image directories for GenXdev.AI image metadata operations. |
| [Set-ComfyUIBackgroundImage](https://github.com/genXdev/GenXdev.AI/tree/main#set-comfyuibackgroundimage) | &nbsp; | Sets or clears the background image for ComfyUI's canvas interface |
| [Set-ComfyUIModelPath](https://github.com/genXdev/GenXdev.AI/tree/main#set-comfyuimodelpath) | &nbsp; | &nbsp; |
| [Set-GenXdevAICommandNotFoundAction](https://github.com/genXdev/GenXdev.AI/tree/main#set-genxdevaicommandnotfoundaction) | &nbsp; | &nbsp; |
| [Set-ImageIndexPath](https://github.com/genXdev/GenXdev.AI/tree/main#set-imageindexpath) | &nbsp; | Sets the default database file path for image operations in GenXdev.AI. |
| [Set-WindowsWallpaperEx](https://github.com/genXdev/GenXdev.AI/tree/main#set-windowswallpaperex) | nextwallpaper | &nbsp; |
| [SetComfyUIProcessPriority](https://github.com/genXdev/GenXdev.AI/tree/main#setcomfyuiprocesspriority) | &nbsp; | &nbsp; |
| [Show-FoundImagesInBrowser](https://github.com/genXdev/GenXdev.AI/tree/main#show-foundimagesinbrowser) | showfoundimages | &nbsp; |
| [Show-GenXdevScriptErrorFixInIde](https://github.com/genXdev/GenXdev.AI/tree/main#show-genxdevscripterrorfixinide) | letsfixthis | &nbsp; |
| [Start-AudioTranscription](https://github.com/genXdev/GenXdev.AI/tree/main#start-audiotranscription) | transcribe, transcribefile | &nbsp; |
| [Start-GenXdevMCPServer](https://github.com/genXdev/GenXdev.AI/tree/main#start-genxdevmcpserver) | &nbsp; | &nbsp; |
| [Start-LMStudioApplication](https://github.com/genXdev/GenXdev.AI/tree/main#start-lmstudioapplication) | &nbsp; | Starts the LM Studio application if it's not already running. |
| [Stop-ComfyUI](https://github.com/genXdev/GenXdev.AI/tree/main#stop-comfyui) | &nbsp; | Terminates all running ComfyUI processes and releases associated resources. |
| [Test-ComfyUIQueueEmpty](https://github.com/genXdev/GenXdev.AI/tree/main#test-comfyuiqueueempty) | &nbsp; | Checks if the ComfyUI processing queue is empty |
| [Test-DeepLinkImageFile](https://github.com/genXdev/GenXdev.AI/tree/main#test-deeplinkimagefile) | &nbsp; | Tests if the specified file path is a valid image file with a supported format. |
| [Test-LMStudioInstallation](https://github.com/genXdev/GenXdev.AI/tree/main#test-lmstudioinstallation) | &nbsp; | Tests if LMStudio is installed and accessible on the system. |
| [Test-LMStudioProcess](https://github.com/genXdev/GenXdev.AI/tree/main#test-lmstudioprocess) | &nbsp; | Tests if LM Studio process is running and configures its window state. |
| [Unregister-AllFaces](https://github.com/genXdev/GenXdev.AI/tree/main#unregister-allfaces) | &nbsp; | Removes all registered faces from the DeepStack face recognition system. |
| [Unregister-Face](https://github.com/genXdev/GenXdev.AI/tree/main#unregister-face) | &nbsp; | Deletes a registered face by its identifier from DeepStack. |
| [Update-AllImageMetaData](https://github.com/genXdev/GenXdev.AI/tree/main#update-allimagemetadata) | updateallimages | &nbsp; |
| [UploadComfyImage](https://github.com/genXdev/GenXdev.AI/tree/main#uploadcomfyimage) | &nbsp; | &nbsp; |
| [WaitForComfyCompletion](https://github.com/genXdev/GenXdev.AI/tree/main#waitforcomfycompletion) | &nbsp; | &nbsp; |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.AI/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.AI.Queries

**A Windows PowerShell module for local AI related operations**

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [Add-EmoticonsToText](https://github.com/genXdev/GenXdev.AI/tree/main#add-emoticonstotext) | emojify | &nbsp; |
| [Add-GenXdevMCPServerToLMStudio](https://github.com/genXdev/GenXdev.AI/tree/main#add-genxdevmcpservertolmstudio) | &nbsp; | Adds the GenXdev MCP server to LM Studio using a deeplink configuration. |
| [Add-ImageDirectories](https://github.com/genXdev/GenXdev.AI/tree/main#add-imagedirectories) | addimgdir | Adds directories to the configured image directories for GenXdev.AI operations. |
| [Approve-NewTextFileContent](https://github.com/genXdev/GenXdev.AI/tree/main#approve-newtextfilecontent) | &nbsp; | Interactive file content comparison and approval using WinMerge. |
| [Compare-ImageFaces](https://github.com/genXdev/GenXdev.AI/tree/main#compare-imagefaces) | comparefaces | &nbsp; |
| [Convert-DotNetTypeToLLMType](https://github.com/genXdev/GenXdev.AI/tree/main#convert-dotnettypetollmtype) | &nbsp; | Converts .NET type names to LLM (Language Model) type names. |
| [ConvertComfyImageFormat](https://github.com/genXdev/GenXdev.AI/tree/main#convertcomfyimageformat) | &nbsp; | Converts image file format while preserving maximum quality. |
| [ConvertFrom-CorporateSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertfrom-corporatespeak) | uncorporatize | &nbsp; |
| [ConvertFrom-DiplomaticSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertfrom-diplomaticspeak) | undiplomatize | &nbsp; |
| [ConvertTo-CorporateSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertto-corporatespeak) | corporatize | &nbsp; |
| [ConvertTo-DiplomaticSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertto-diplomaticspeak) | diplomatize | &nbsp; |
| [ConvertTo-LMStudioFunctionDefinition](https://github.com/genXdev/GenXdev.AI/tree/main#convertto-lmstudiofunctiondefinition) | &nbsp; | &nbsp; |
| [CreateComfySDXLWorkflow](https://github.com/genXdev/GenXdev.AI/tree/main#createcomfysdxlworkflow) | &nbsp; | Creates comprehensive ComfyUI SDXL workflow configuration supporting all parameters |
| [CreateComfyUniversalWorkflow](https://github.com/genXdev/GenXdev.AI/tree/main#createcomfyuniversalworkflow) | &nbsp; | &nbsp; |
| [DownloadComfyResults](https://github.com/genXdev/GenXdev.AI/tree/main#downloadcomfyresults) | &nbsp; | Downloads generated results from ComfyUI server with file information |
| [EnsureComfyUI](https://github.com/genXdev/GenXdev.AI/tree/main#ensurecomfyui) | &nbsp; | Ensures ComfyUI is installed and running with optional window positioning. |
| [EnsureComfyUIModel](https://github.com/genXdev/GenXdev.AI/tree/main#ensurecomfyuimodel) | &nbsp; | Ensures specified ComfyUI models are available locally with automatic download |
| [EnsureDeepStack](https://github.com/genXdev/GenXdev.AI/tree/main#ensuredeepstack) | &nbsp; | &nbsp; |
| [EnsureGithubCLIInstalled](https://github.com/genXdev/GenXdev.AI/tree/main#ensuregithubcliinstalled) | &nbsp; | Ensures GitHub CLI is properly installed and configured on the system. |
| [EnsureHuggingFace](https://github.com/genXdev/GenXdev.AI/tree/main#ensurehuggingface) | &nbsp; | &nbsp; |
| [EnsureLMStudio](https://github.com/genXdev/GenXdev.AI/tree/main#ensurelmstudio) | &nbsp; | &nbsp; |
| [EnsurePaintNet](https://github.com/genXdev/GenXdev.AI/tree/main#ensurepaintnet) | &nbsp; | Ensures Paint.NET is properly installed and accessible on the system. |
| [EnsurePip](https://github.com/genXdev/GenXdev.AI/tree/main#ensurepip) | &nbsp; | Ensures pip is installed and functional for the specified Python installation. |
| [EnsurePython](https://github.com/genXdev/GenXdev.AI/tree/main#ensurepython) | &nbsp; | &nbsp; |
| [EnsureWinMergeInstalled](https://github.com/genXdev/GenXdev.AI/tree/main#ensurewinmergeinstalled) | &nbsp; | Ensures WinMerge is installed and available for file comparison operations. |
| [Export-ImageIndex](https://github.com/genXdev/GenXdev.AI/tree/main#export-imageindex) | indeximages | &nbsp; |
| [Find-Image](https://github.com/genXdev/GenXdev.AI/tree/main#find-image) | findimages, li | &nbsp; |
| [Find-IndexedImage](https://github.com/genXdev/GenXdev.AI/tree/main#find-indexedimage) | findindexedimages, lii | &nbsp; |
| [GenerateMasonryLayoutHtml](https://github.com/genXdev/GenXdev.AI/tree/main#generatemasonrylayouthtml) | &nbsp; | Generates a responsive masonry layout HTML gallery from image data. |
| [Get-AIDefaultLLMSettings](https://github.com/genXdev/GenXdev.AI/tree/main#get-aidefaultllmsettings) | &nbsp; | &nbsp; |
| [Get-AIImageCollection](https://github.com/genXdev/GenXdev.AI/tree/main#get-aiimagecollection) | getimgdirs | &nbsp; |
| [Get-AIKnownFacesRootpath](https://github.com/genXdev/GenXdev.AI/tree/main#get-aiknownfacesrootpath) | &nbsp; | Gets the configured directory for face image files used in GenXdev.AI operations. |
| [Get-AILLMSettings](https://github.com/genXdev/GenXdev.AI/tree/main#get-aillmsettings) | &nbsp; | &nbsp; |
| [Get-AIMetaLanguage](https://github.com/genXdev/GenXdev.AI/tree/main#get-aimetalanguage) | getimgmetalang | Gets the configured default language for image metadata operations. |
| [Get-ComfyUIModelPath](https://github.com/genXdev/GenXdev.AI/tree/main#get-comfyuimodelpath) | &nbsp; | Gets the correct ComfyUI models directory path for the current installation |
| [Get-CpuCore](https://github.com/genXdev/GenXdev.AI/tree/main#get-cpucore) | &nbsp; | Calculates and returns the total number of logical CPU cores in the system. |
| [Get-Fallacy](https://github.com/genXdev/GenXdev.AI/tree/main#get-fallacy) | dispicetext | &nbsp; |
| [Get-HasCapableGpu](https://github.com/genXdev/GenXdev.AI/tree/main#get-hascapablegpu) | &nbsp; | Determines if a CUDA-capable GPU with sufficient memory is present. |
| [Get-ImageDetectedFaces](https://github.com/genXdev/GenXdev.AI/tree/main#get-imagedetectedfaces) | &nbsp; | &nbsp; |
| [Get-ImageDetectedObjects](https://github.com/genXdev/GenXdev.AI/tree/main#get-imagedetectedobjects) | &nbsp; | Detects and classifies objects in an uploaded image using DeepStack. |
| [Get-ImageDetectedScenes](https://github.com/genXdev/GenXdev.AI/tree/main#get-imagedetectedscenes) | &nbsp; | &nbsp; |
| [Get-ImageIndexPath](https://github.com/genXdev/GenXdev.AI/tree/main#get-imageindexpath) | &nbsp; | Returns the path to the image database, initializing or rebuilding it if needed. |
| [Get-ImageIndexStats](https://github.com/genXdev/GenXdev.AI/tree/main#get-imageindexstats) | getimagedbstats, gids | &nbsp; |
| [Get-LMStudioLoadedModelList](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudioloadedmodellist) | &nbsp; | Retrieves the list of currently loaded models from LM Studio. |
| [Get-LMStudioModelList](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiomodellist) | &nbsp; | Retrieves a list of installed LM Studio models. |
| [Get-LMStudioPaths](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiopaths) | &nbsp; | Retrieves file paths for LM Studio executables. |
| [Get-LMStudioTextEmbedding](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiotextembedding) | &nbsp; | Gets text embeddings from LM Studio model. |
| [Get-LMStudioWindow](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiowindow) | lmstudiowindow, setlmstudiowindow | Gets a window helper for the LM Studio application. |
| [Get-NumberOfCpuCores](https://github.com/genXdev/GenXdev.AI/tree/main#get-numberofcpucores) | &nbsp; | Calculates and returns the total number of logical CPU cores in the system. |
| [Get-RegisteredFaces](https://github.com/genXdev/GenXdev.AI/tree/main#get-registeredfaces) | &nbsp; | &nbsp; |
| [Get-ScriptExecutionErrorFixPrompt](https://github.com/genXdev/GenXdev.AI/tree/main#get-scriptexecutionerrorfixprompt) | getfixprompt | &nbsp; |
| [Get-SimularMovieTitles](https://github.com/genXdev/GenXdev.AI/tree/main#get-simularmovietitles) | &nbsp; | Finds similar movie titles based on common properties. |
| [Get-TextTranslation](https://github.com/genXdev/GenXdev.AI/tree/main#get-texttranslation) | translate | &nbsp; |
| [Get-VectorSimilarity](https://github.com/genXdev/GenXdev.AI/tree/main#get-vectorsimilarity) | &nbsp; | Calculates the cosine similarity between two vectors, returning a value between 0 and 1. |
| [Initialize-LMStudioModel](https://github.com/genXdev/GenXdev.AI/tree/main#initialize-lmstudiomodel) | initlmstudio | &nbsp; |
| [Install-LMStudioApplication](https://github.com/genXdev/GenXdev.AI/tree/main#install-lmstudioapplication) | &nbsp; | Installs LM Studio application using WinGet package manager. |
| [Invoke-AIPowershellCommand](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-aipowershellcommand) | hint | &nbsp; |
| [Invoke-ComfyUIImageGeneration](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-comfyuiimagegeneration) | generateimage | &nbsp; |
| [Invoke-CommandFromToolCall](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-commandfromtoolcall) | &nbsp; | &nbsp; |
| [Invoke-HuggingFaceCli](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-huggingfacecli) | &nbsp; | &nbsp; |
| [Invoke-ImageEnhancement](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imageenhancement) | enhanceimage | &nbsp; |
| [Invoke-ImageFacesUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagefacesupdate) | imagepeopledetection | &nbsp; |
| [Invoke-ImageKeywordUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagekeywordupdate) | imagekeywordgeneration | &nbsp; |
| [Invoke-ImageMetadataUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagemetadataupdate) | imagepropdetection | &nbsp; |
| [Invoke-ImageObjectsUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imageobjectsupdate) | imageobjectdetection | &nbsp; |
| [Invoke-ImageScenesUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagescenesupdate) | imagescenedetection | &nbsp; |
| [Invoke-LLMBooleanEvaluation](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmbooleanevaluation) | equalstrue | &nbsp; |
| [Invoke-LLMQuery](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmquery) | llm, qllm | &nbsp; |
| [Invoke-LLMStringListEvaluation](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmstringlistevaluation) | getlist, getstring | &nbsp; |
| [Invoke-LLMTextTransformation](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmtexttransformation) | spellcheck | &nbsp; |
| [Invoke-QueryImageContent](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-queryimagecontent) | &nbsp; | &nbsp; |
| [Invoke-WinMerge](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-winmerge) | &nbsp; | Launches WinMerge to compare two files side by side. |
| [New-LLMAudioChat](https://github.com/genXdev/GenXdev.AI/tree/main#new-llmaudiochat) | llmaudiochat | &nbsp; |
| [New-LLMTextChat](https://github.com/genXdev/GenXdev.AI/tree/main#new-llmtextchat) | llmchat | &nbsp; |
| [QueueComfyWorkflow](https://github.com/genXdev/GenXdev.AI/tree/main#queuecomfyworkflow) | &nbsp; | &nbsp; |
| [Register-AllFaces](https://github.com/genXdev/GenXdev.AI/tree/main#register-allfaces) | UpdateFaces | &nbsp; |
| [Register-Face](https://github.com/genXdev/GenXdev.AI/tree/main#register-face) | &nbsp; | &nbsp; |
| [Remove-ImageDirectories](https://github.com/genXdev/GenXdev.AI/tree/main#remove-imagedirectories) | removeimgdir | &nbsp; |
| [Remove-ImageMetaData](https://github.com/genXdev/GenXdev.AI/tree/main#remove-imagemetadata) | removeimagedata | &nbsp; |
| [ResizeComfyInputImage](https://github.com/genXdev/GenXdev.AI/tree/main#resizecomfyinputimage) | &nbsp; | &nbsp; |
| [Save-FoundImageFaces](https://github.com/genXdev/GenXdev.AI/tree/main#save-foundimagefaces) | saveimagefaces | &nbsp; |
| [Save-FoundImageObjects](https://github.com/genXdev/GenXdev.AI/tree/main#save-foundimageobjects) | saveimageObjects | &nbsp; |
| [Save-Transcriptions](https://github.com/genXdev/GenXdev.AI/tree/main#save-transcriptions) | &nbsp; | &nbsp; |
| [Set-AIImageCollection](https://github.com/genXdev/GenXdev.AI/tree/main#set-aiimagecollection) | &nbsp; | &nbsp; |
| [Set-AIKnownFacesRootpath](https://github.com/genXdev/GenXdev.AI/tree/main#set-aiknownfacesrootpath) | &nbsp; | Sets the directory for face image files used in GenXdev.AI operations. |
| [Set-AILLMSettings](https://github.com/genXdev/GenXdev.AI/tree/main#set-aillmsettings) | &nbsp; | &nbsp; |
| [Set-AIMetaLanguage](https://github.com/genXdev/GenXdev.AI/tree/main#set-aimetalanguage) | &nbsp; | Sets the default language and optionally the image directories for GenXdev.AI image metadata operations. |
| [Set-ComfyUIBackgroundImage](https://github.com/genXdev/GenXdev.AI/tree/main#set-comfyuibackgroundimage) | &nbsp; | Sets or clears the background image for ComfyUI's canvas interface |
| [Set-ComfyUIModelPath](https://github.com/genXdev/GenXdev.AI/tree/main#set-comfyuimodelpath) | &nbsp; | &nbsp; |
| [Set-GenXdevAICommandNotFoundAction](https://github.com/genXdev/GenXdev.AI/tree/main#set-genxdevaicommandnotfoundaction) | &nbsp; | &nbsp; |
| [Set-ImageIndexPath](https://github.com/genXdev/GenXdev.AI/tree/main#set-imageindexpath) | &nbsp; | Sets the default database file path for image operations in GenXdev.AI. |
| [Set-WindowsWallpaperEx](https://github.com/genXdev/GenXdev.AI/tree/main#set-windowswallpaperex) | nextwallpaper | &nbsp; |
| [SetComfyUIProcessPriority](https://github.com/genXdev/GenXdev.AI/tree/main#setcomfyuiprocesspriority) | &nbsp; | &nbsp; |
| [Show-FoundImagesInBrowser](https://github.com/genXdev/GenXdev.AI/tree/main#show-foundimagesinbrowser) | showfoundimages | &nbsp; |
| [Show-GenXdevScriptErrorFixInIde](https://github.com/genXdev/GenXdev.AI/tree/main#show-genxdevscripterrorfixinide) | letsfixthis | &nbsp; |
| [Start-AudioTranscription](https://github.com/genXdev/GenXdev.AI/tree/main#start-audiotranscription) | transcribe, transcribefile | &nbsp; |
| [Start-GenXdevMCPServer](https://github.com/genXdev/GenXdev.AI/tree/main#start-genxdevmcpserver) | &nbsp; | &nbsp; |
| [Start-LMStudioApplication](https://github.com/genXdev/GenXdev.AI/tree/main#start-lmstudioapplication) | &nbsp; | Starts the LM Studio application if it's not already running. |
| [Stop-ComfyUI](https://github.com/genXdev/GenXdev.AI/tree/main#stop-comfyui) | &nbsp; | Terminates all running ComfyUI processes and releases associated resources. |
| [Test-ComfyUIQueueEmpty](https://github.com/genXdev/GenXdev.AI/tree/main#test-comfyuiqueueempty) | &nbsp; | Checks if the ComfyUI processing queue is empty |
| [Test-DeepLinkImageFile](https://github.com/genXdev/GenXdev.AI/tree/main#test-deeplinkimagefile) | &nbsp; | Tests if the specified file path is a valid image file with a supported format. |
| [Test-LMStudioInstallation](https://github.com/genXdev/GenXdev.AI/tree/main#test-lmstudioinstallation) | &nbsp; | Tests if LMStudio is installed and accessible on the system. |
| [Test-LMStudioProcess](https://github.com/genXdev/GenXdev.AI/tree/main#test-lmstudioprocess) | &nbsp; | Tests if LM Studio process is running and configures its window state. |
| [Unregister-AllFaces](https://github.com/genXdev/GenXdev.AI/tree/main#unregister-allfaces) | &nbsp; | Removes all registered faces from the DeepStack face recognition system. |
| [Unregister-Face](https://github.com/genXdev/GenXdev.AI/tree/main#unregister-face) | &nbsp; | Deletes a registered face by its identifier from DeepStack. |
| [Update-AllImageMetaData](https://github.com/genXdev/GenXdev.AI/tree/main#update-allimagemetadata) | updateallimages | &nbsp; |
| [UploadComfyImage](https://github.com/genXdev/GenXdev.AI/tree/main#uploadcomfyimage) | &nbsp; | &nbsp; |
| [WaitForComfyCompletion](https://github.com/genXdev/GenXdev.AI/tree/main#waitforcomfycompletion) | &nbsp; | &nbsp; |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.AI/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Coding

**A Windows PowerShell module that helps being more productive with coding tasks.**

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [Add-FeatureLineToREADME](https://github.com/genXdev/GenXdev.Coding/tree/main#add-featurelinetoreadme) | feature | Adds a feature line to the README file with a timestamp. |
| [Add-IdeaLineToREADME](https://github.com/genXdev/GenXdev.Coding/tree/main#add-idealinetoreadme) | idea | Adds an idea item to the README.md file. |
| [Add-IssueLineToREADME](https://github.com/genXdev/GenXdev.Coding/tree/main#add-issuelinetoreadme) | issue | Adds an issue item to the README.md file. |
| [Add-LineToREADME](https://github.com/genXdev/GenXdev.Coding/tree/main#add-linetoreadme) | &nbsp; | &nbsp; |
| [Add-MissingGenXdevUnitTests](https://github.com/genXdev/GenXdev.Coding/tree/main#add-missinggenxdevunittests) | &nbsp; | &nbsp; |
| [Add-ReleaseNoteLineToREADME](https://github.com/genXdev/GenXdev.Coding/tree/main#add-releasenotelinetoreadme) | releasenote | Adds a ReleaseNote line to the README file with a timestamp. |
| [Add-TodoLineToREADME](https://github.com/genXdev/GenXdev.Coding/tree/main#add-todolinetoreadme) | todo | Adds a todo item to the README.md file. |
| [Assert-GenXdevCmdlet](https://github.com/genXdev/GenXdev.Coding/tree/main#assert-genxdevcmdlet) | improvecmdlet | Improves GenXdev cmdlet documentation and implementation through AI assistance. |
| [Assert-GenXdevCmdletTests](https://github.com/genXdev/GenXdev.Coding/tree/main#assert-genxdevcmdlettests) | improvecmdlettests | Asserts and improves unit-tests of a specified GenXdev cmdlet. |
| [Assert-GenXdevDependencyUsage](https://github.com/genXdev/GenXdev.Coding/tree/main#assert-genxdevdependencyusage) | checkgenxdevdependencies | &nbsp; |
| [Assert-GenXdevTest](https://github.com/genXdev/GenXdev.Coding/tree/main#assert-genxdevtest) | rungenxdevtests | &nbsp; |
| [Assert-ModuleDefinition](https://github.com/genXdev/GenXdev.Coding/tree/main#assert-moduledefinition) | &nbsp; | &nbsp; |
| [Assert-RefactorFile](https://github.com/genXdev/GenXdev.Coding/tree/main#assert-refactorfile) | &nbsp; | &nbsp; |
| [Clear-GenXdevModules](https://github.com/genXdev/GenXdev.Coding/tree/main#clear-genxdevmodules) | cleangenxdev | Cleans build artifacts from GenXdev PowerShell modules. |
| [Complete-GenXdevHelpFile](https://github.com/genXdev/GenXdev.Coding/tree/main#complete-genxdevhelpfile) | &nbsp; | &nbsp; |
| [Complete-GenXDevREADME](https://github.com/genXdev/GenXdev.Coding/tree/main#complete-genxdevreadme) | &nbsp; | &nbsp; |
| [EnsureCopilotKeyboardShortCut](https://github.com/genXdev/GenXdev.Coding/tree/main#ensurecopilotkeyboardshortcut) | &nbsp; | Configures the GitHub Copilot Chat keyboard shortcuts in Visual Studio Code. |
| [EnsureDefaultGenXdevRefactors](https://github.com/genXdev/GenXdev.Coding/tree/main#ensuredefaultgenxdevrefactors) | &nbsp; | &nbsp; |
| [EnsureVSCodeInstallation](https://github.com/genXdev/GenXdev.Coding/tree/main#ensurevscodeinstallation) | &nbsp; | Installs and configures Visual Studio Code with recommended extensions. |
| [Features](https://github.com/genXdev/GenXdev.Coding/tree/main#features) | &nbsp; | Displays features from a README.md file. |
| [Get-GenXdevCmdletUsageAnalysis](https://github.com/genXdev/GenXdev.Coding/tree/main#get-genxdevcmdletusageanalysis) | &nbsp; | &nbsp; |
| [Get-GenXDevModule](https://github.com/genXdev/GenXdev.Coding/tree/main#get-genxdevmodule) | &nbsp; | Retrieves all GenXDev modules from a specified path. |
| [Get-GenXDevModuleinfo](https://github.com/genXdev/GenXdev.Coding/tree/main#get-genxdevmoduleinfo) | &nbsp; | &nbsp; |
| [Get-GenXDevNewModulesInOrderOfDependency](https://github.com/genXdev/GenXdev.Coding/tree/main#get-genxdevnewmodulesinorderofdependency) | &nbsp; | Retrieves GenXDev modules in dependency order. |
| [Get-GitChangedFiles](https://github.com/genXdev/GenXdev.Coding/tree/main#get-gitchangedfiles) | gitchanged | Get the list of changed files in a Git repository. |
| [Get-ModuleHelpMarkdown](https://github.com/genXdev/GenXdev.Coding/tree/main#get-modulehelpmarkdown) | &nbsp; | &nbsp; |
| [Get-Refactor](https://github.com/genXdev/GenXdev.Coding/tree/main#get-refactor) | refactors | &nbsp; |
| [Get-RefactorReport](https://github.com/genXdev/GenXdev.Coding/tree/main#get-refactorreport) | refactorreport | Generates a detailed report of refactoring operations and their status. |
| [Ideas](https://github.com/genXdev/GenXdev.Coding/tree/main#ideas) | &nbsp; | &nbsp; |
| [Invoke-GenXdevPSFormatter](https://github.com/genXdev/GenXdev.Coding/tree/main#invoke-genxdevpsformatter) | &nbsp; | &nbsp; |
| [Invoke-GenXdevScriptAnalyzer](https://github.com/genXdev/GenXdev.Coding/tree/main#invoke-genxdevscriptanalyzer) | &nbsp; | &nbsp; |
| [Issues](https://github.com/genXdev/GenXdev.Coding/tree/main#issues) | &nbsp; | &nbsp; |
| [New-GenXdevCmdlet](https://github.com/genXdev/GenXdev.Coding/tree/main#new-genxdevcmdlet) | newcmd | Creates a new GenXdev PowerShell cmdlet with proper structure and validation. |
| [New-GenXdevModule](https://github.com/genXdev/GenXdev.Coding/tree/main#new-genxdevmodule) | &nbsp; | &nbsp; |
| [New-GitCommit](https://github.com/genXdev/GenXdev.Coding/tree/main#new-gitcommit) | commit | Creates and pushes a new git commit with all changes. |
| [New-PullRequestForGenXdevModuleChanges](https://github.com/genXdev/GenXdev.Coding/tree/main#new-pullrequestforgenxdevmodulechanges) | prgenxdevmodule | Creates a pull request for changes made to a GenXdev module. |
| [New-Refactor](https://github.com/genXdev/GenXdev.Coding/tree/main#new-refactor) | newrefactor | &nbsp; |
| [Open-GenXdevCmdletsContainingClipboardTextInIde](https://github.com/genXdev/GenXdev.Coding/tree/main#open-genxdevcmdletscontainingclipboardtextinide) | vscodesearch | Opens files in IDE that contain clipboard text |
| [Open-SourceFileInIde](https://github.com/genXdev/GenXdev.Coding/tree/main#open-sourcefileinide) | editcode | &nbsp; |
| [PermanentlyDeleteGitFolders](https://github.com/genXdev/GenXdev.Coding/tree/main#permanentlydeletegitfolders) | &nbsp; | Permanently deletes specified folders from all branches in a Git repository. |
| [ReleaseNotes](https://github.com/genXdev/GenXdev.Coding/tree/main#releasenotes) | &nbsp; | &nbsp; |
| [Remove-Refactor](https://github.com/genXdev/GenXdev.Coding/tree/main#remove-refactor) | &nbsp; | Removes refactor sets from GenXdev preferences system. |
| [Search-GenXdevCmdlet](https://github.com/genXdev/GenXdev.Coding/tree/main#search-genxdevcmdlet) | searchcmdlet | Searches for a GenXdev cmdlet and optionally opens it in an IDE for editing. |
| [Show-GenXdevCmdLetInIde](https://github.com/genXdev/GenXdev.Coding/tree/main#show-genxdevcmdletinide) | cmdlet, editcmdlet | Opens the specified GenXdev cmdlet in Visual Studio Code. |
| [SplitUpPsm1File](https://github.com/genXdev/GenXdev.Coding/tree/main#splituppsm1file) | &nbsp; | &nbsp; |
| [Start-NextRefactor](https://github.com/genXdev/GenXdev.Coding/tree/main#start-nextrefactor) | nextrefactor | &nbsp; |
| [Test-RefactorLLMSelection](https://github.com/genXdev/GenXdev.Coding/tree/main#test-refactorllmselection) | &nbsp; | Evaluates source files for refactoring eligibility using LLM analysis. |
| [Todoos](https://github.com/genXdev/GenXdev.Coding/tree/main#todoos) | &nbsp; | &nbsp; |
| [Update-Refactor](https://github.com/genXdev/GenXdev.Coding/tree/main#update-refactor) | updaterefactor | &nbsp; |
| [VSCode](https://github.com/genXdev/GenXdev.Coding/tree/main#vscode) | &nbsp; | &nbsp; |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Coding.Git

**A Windows PowerShell module that helps being more productive with coding tasks.**

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [Add-FeatureLineToREADME](https://github.com/genXdev/GenXdev.Coding/tree/main#add-featurelinetoreadme) | feature | Adds a feature line to the README file with a timestamp. |
| [Add-IdeaLineToREADME](https://github.com/genXdev/GenXdev.Coding/tree/main#add-idealinetoreadme) | idea | Adds an idea item to the README.md file. |
| [Add-IssueLineToREADME](https://github.com/genXdev/GenXdev.Coding/tree/main#add-issuelinetoreadme) | issue | Adds an issue item to the README.md file. |
| [Add-LineToREADME](https://github.com/genXdev/GenXdev.Coding/tree/main#add-linetoreadme) | &nbsp; | &nbsp; |
| [Add-MissingGenXdevUnitTests](https://github.com/genXdev/GenXdev.Coding/tree/main#add-missinggenxdevunittests) | &nbsp; | &nbsp; |
| [Add-ReleaseNoteLineToREADME](https://github.com/genXdev/GenXdev.Coding/tree/main#add-releasenotelinetoreadme) | releasenote | Adds a ReleaseNote line to the README file with a timestamp. |
| [Add-TodoLineToREADME](https://github.com/genXdev/GenXdev.Coding/tree/main#add-todolinetoreadme) | todo | Adds a todo item to the README.md file. |
| [Assert-GenXdevCmdlet](https://github.com/genXdev/GenXdev.Coding/tree/main#assert-genxdevcmdlet) | improvecmdlet | Improves GenXdev cmdlet documentation and implementation through AI assistance. |
| [Assert-GenXdevCmdletTests](https://github.com/genXdev/GenXdev.Coding/tree/main#assert-genxdevcmdlettests) | improvecmdlettests | Asserts and improves unit-tests of a specified GenXdev cmdlet. |
| [Assert-GenXdevDependencyUsage](https://github.com/genXdev/GenXdev.Coding/tree/main#assert-genxdevdependencyusage) | checkgenxdevdependencies | &nbsp; |
| [Assert-GenXdevTest](https://github.com/genXdev/GenXdev.Coding/tree/main#assert-genxdevtest) | rungenxdevtests | &nbsp; |
| [Assert-ModuleDefinition](https://github.com/genXdev/GenXdev.Coding/tree/main#assert-moduledefinition) | &nbsp; | &nbsp; |
| [Assert-RefactorFile](https://github.com/genXdev/GenXdev.Coding/tree/main#assert-refactorfile) | &nbsp; | &nbsp; |
| [Clear-GenXdevModules](https://github.com/genXdev/GenXdev.Coding/tree/main#clear-genxdevmodules) | cleangenxdev | Cleans build artifacts from GenXdev PowerShell modules. |
| [Complete-GenXdevHelpFile](https://github.com/genXdev/GenXdev.Coding/tree/main#complete-genxdevhelpfile) | &nbsp; | &nbsp; |
| [Complete-GenXDevREADME](https://github.com/genXdev/GenXdev.Coding/tree/main#complete-genxdevreadme) | &nbsp; | &nbsp; |
| [EnsureCopilotKeyboardShortCut](https://github.com/genXdev/GenXdev.Coding/tree/main#ensurecopilotkeyboardshortcut) | &nbsp; | Configures the GitHub Copilot Chat keyboard shortcuts in Visual Studio Code. |
| [EnsureDefaultGenXdevRefactors](https://github.com/genXdev/GenXdev.Coding/tree/main#ensuredefaultgenxdevrefactors) | &nbsp; | &nbsp; |
| [EnsureVSCodeInstallation](https://github.com/genXdev/GenXdev.Coding/tree/main#ensurevscodeinstallation) | &nbsp; | Installs and configures Visual Studio Code with recommended extensions. |
| [Features](https://github.com/genXdev/GenXdev.Coding/tree/main#features) | &nbsp; | Displays features from a README.md file. |
| [Get-GenXdevCmdletUsageAnalysis](https://github.com/genXdev/GenXdev.Coding/tree/main#get-genxdevcmdletusageanalysis) | &nbsp; | &nbsp; |
| [Get-GenXDevModule](https://github.com/genXdev/GenXdev.Coding/tree/main#get-genxdevmodule) | &nbsp; | Retrieves all GenXDev modules from a specified path. |
| [Get-GenXDevModuleinfo](https://github.com/genXdev/GenXdev.Coding/tree/main#get-genxdevmoduleinfo) | &nbsp; | &nbsp; |
| [Get-GenXDevNewModulesInOrderOfDependency](https://github.com/genXdev/GenXdev.Coding/tree/main#get-genxdevnewmodulesinorderofdependency) | &nbsp; | Retrieves GenXDev modules in dependency order. |
| [Get-GitChangedFiles](https://github.com/genXdev/GenXdev.Coding/tree/main#get-gitchangedfiles) | gitchanged | Get the list of changed files in a Git repository. |
| [Get-ModuleHelpMarkdown](https://github.com/genXdev/GenXdev.Coding/tree/main#get-modulehelpmarkdown) | &nbsp; | &nbsp; |
| [Get-Refactor](https://github.com/genXdev/GenXdev.Coding/tree/main#get-refactor) | refactors | &nbsp; |
| [Get-RefactorReport](https://github.com/genXdev/GenXdev.Coding/tree/main#get-refactorreport) | refactorreport | Generates a detailed report of refactoring operations and their status. |
| [Ideas](https://github.com/genXdev/GenXdev.Coding/tree/main#ideas) | &nbsp; | &nbsp; |
| [Invoke-GenXdevPSFormatter](https://github.com/genXdev/GenXdev.Coding/tree/main#invoke-genxdevpsformatter) | &nbsp; | &nbsp; |
| [Invoke-GenXdevScriptAnalyzer](https://github.com/genXdev/GenXdev.Coding/tree/main#invoke-genxdevscriptanalyzer) | &nbsp; | &nbsp; |
| [Issues](https://github.com/genXdev/GenXdev.Coding/tree/main#issues) | &nbsp; | &nbsp; |
| [New-GenXdevCmdlet](https://github.com/genXdev/GenXdev.Coding/tree/main#new-genxdevcmdlet) | newcmd | Creates a new GenXdev PowerShell cmdlet with proper structure and validation. |
| [New-GenXdevModule](https://github.com/genXdev/GenXdev.Coding/tree/main#new-genxdevmodule) | &nbsp; | &nbsp; |
| [New-GitCommit](https://github.com/genXdev/GenXdev.Coding/tree/main#new-gitcommit) | commit | Creates and pushes a new git commit with all changes. |
| [New-PullRequestForGenXdevModuleChanges](https://github.com/genXdev/GenXdev.Coding/tree/main#new-pullrequestforgenxdevmodulechanges) | prgenxdevmodule | Creates a pull request for changes made to a GenXdev module. |
| [New-Refactor](https://github.com/genXdev/GenXdev.Coding/tree/main#new-refactor) | newrefactor | &nbsp; |
| [Open-GenXdevCmdletsContainingClipboardTextInIde](https://github.com/genXdev/GenXdev.Coding/tree/main#open-genxdevcmdletscontainingclipboardtextinide) | vscodesearch | Opens files in IDE that contain clipboard text |
| [Open-SourceFileInIde](https://github.com/genXdev/GenXdev.Coding/tree/main#open-sourcefileinide) | editcode | &nbsp; |
| [PermanentlyDeleteGitFolders](https://github.com/genXdev/GenXdev.Coding/tree/main#permanentlydeletegitfolders) | &nbsp; | Permanently deletes specified folders from all branches in a Git repository. |
| [ReleaseNotes](https://github.com/genXdev/GenXdev.Coding/tree/main#releasenotes) | &nbsp; | &nbsp; |
| [Remove-Refactor](https://github.com/genXdev/GenXdev.Coding/tree/main#remove-refactor) | &nbsp; | Removes refactor sets from GenXdev preferences system. |
| [Search-GenXdevCmdlet](https://github.com/genXdev/GenXdev.Coding/tree/main#search-genxdevcmdlet) | searchcmdlet | Searches for a GenXdev cmdlet and optionally opens it in an IDE for editing. |
| [Show-GenXdevCmdLetInIde](https://github.com/genXdev/GenXdev.Coding/tree/main#show-genxdevcmdletinide) | cmdlet, editcmdlet | Opens the specified GenXdev cmdlet in Visual Studio Code. |
| [SplitUpPsm1File](https://github.com/genXdev/GenXdev.Coding/tree/main#splituppsm1file) | &nbsp; | &nbsp; |
| [Start-NextRefactor](https://github.com/genXdev/GenXdev.Coding/tree/main#start-nextrefactor) | nextrefactor | &nbsp; |
| [Test-RefactorLLMSelection](https://github.com/genXdev/GenXdev.Coding/tree/main#test-refactorllmselection) | &nbsp; | Evaluates source files for refactoring eligibility using LLM analysis. |
| [Todoos](https://github.com/genXdev/GenXdev.Coding/tree/main#todoos) | &nbsp; | &nbsp; |
| [Update-Refactor](https://github.com/genXdev/GenXdev.Coding/tree/main#update-refactor) | updaterefactor | &nbsp; |
| [VSCode](https://github.com/genXdev/GenXdev.Coding/tree/main#vscode) | &nbsp; | &nbsp; |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Coding.PowerShell.Modules

**A Windows PowerShell module that helps being more productive with coding tasks.**

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [Add-FeatureLineToREADME](https://github.com/genXdev/GenXdev.Coding/tree/main#add-featurelinetoreadme) | feature | Adds a feature line to the README file with a timestamp. |
| [Add-IdeaLineToREADME](https://github.com/genXdev/GenXdev.Coding/tree/main#add-idealinetoreadme) | idea | Adds an idea item to the README.md file. |
| [Add-IssueLineToREADME](https://github.com/genXdev/GenXdev.Coding/tree/main#add-issuelinetoreadme) | issue | Adds an issue item to the README.md file. |
| [Add-LineToREADME](https://github.com/genXdev/GenXdev.Coding/tree/main#add-linetoreadme) | &nbsp; | &nbsp; |
| [Add-MissingGenXdevUnitTests](https://github.com/genXdev/GenXdev.Coding/tree/main#add-missinggenxdevunittests) | &nbsp; | &nbsp; |
| [Add-ReleaseNoteLineToREADME](https://github.com/genXdev/GenXdev.Coding/tree/main#add-releasenotelinetoreadme) | releasenote | Adds a ReleaseNote line to the README file with a timestamp. |
| [Add-TodoLineToREADME](https://github.com/genXdev/GenXdev.Coding/tree/main#add-todolinetoreadme) | todo | Adds a todo item to the README.md file. |
| [Assert-GenXdevCmdlet](https://github.com/genXdev/GenXdev.Coding/tree/main#assert-genxdevcmdlet) | improvecmdlet | Improves GenXdev cmdlet documentation and implementation through AI assistance. |
| [Assert-GenXdevCmdletTests](https://github.com/genXdev/GenXdev.Coding/tree/main#assert-genxdevcmdlettests) | improvecmdlettests | Asserts and improves unit-tests of a specified GenXdev cmdlet. |
| [Assert-GenXdevDependencyUsage](https://github.com/genXdev/GenXdev.Coding/tree/main#assert-genxdevdependencyusage) | checkgenxdevdependencies | &nbsp; |
| [Assert-GenXdevTest](https://github.com/genXdev/GenXdev.Coding/tree/main#assert-genxdevtest) | rungenxdevtests | &nbsp; |
| [Assert-ModuleDefinition](https://github.com/genXdev/GenXdev.Coding/tree/main#assert-moduledefinition) | &nbsp; | &nbsp; |
| [Assert-RefactorFile](https://github.com/genXdev/GenXdev.Coding/tree/main#assert-refactorfile) | &nbsp; | &nbsp; |
| [Clear-GenXdevModules](https://github.com/genXdev/GenXdev.Coding/tree/main#clear-genxdevmodules) | cleangenxdev | Cleans build artifacts from GenXdev PowerShell modules. |
| [Complete-GenXdevHelpFile](https://github.com/genXdev/GenXdev.Coding/tree/main#complete-genxdevhelpfile) | &nbsp; | &nbsp; |
| [Complete-GenXDevREADME](https://github.com/genXdev/GenXdev.Coding/tree/main#complete-genxdevreadme) | &nbsp; | &nbsp; |
| [EnsureCopilotKeyboardShortCut](https://github.com/genXdev/GenXdev.Coding/tree/main#ensurecopilotkeyboardshortcut) | &nbsp; | Configures the GitHub Copilot Chat keyboard shortcuts in Visual Studio Code. |
| [EnsureDefaultGenXdevRefactors](https://github.com/genXdev/GenXdev.Coding/tree/main#ensuredefaultgenxdevrefactors) | &nbsp; | &nbsp; |
| [EnsureVSCodeInstallation](https://github.com/genXdev/GenXdev.Coding/tree/main#ensurevscodeinstallation) | &nbsp; | Installs and configures Visual Studio Code with recommended extensions. |
| [Features](https://github.com/genXdev/GenXdev.Coding/tree/main#features) | &nbsp; | Displays features from a README.md file. |
| [Get-GenXdevCmdletUsageAnalysis](https://github.com/genXdev/GenXdev.Coding/tree/main#get-genxdevcmdletusageanalysis) | &nbsp; | &nbsp; |
| [Get-GenXDevModule](https://github.com/genXdev/GenXdev.Coding/tree/main#get-genxdevmodule) | &nbsp; | Retrieves all GenXDev modules from a specified path. |
| [Get-GenXDevModuleinfo](https://github.com/genXdev/GenXdev.Coding/tree/main#get-genxdevmoduleinfo) | &nbsp; | &nbsp; |
| [Get-GenXDevNewModulesInOrderOfDependency](https://github.com/genXdev/GenXdev.Coding/tree/main#get-genxdevnewmodulesinorderofdependency) | &nbsp; | Retrieves GenXDev modules in dependency order. |
| [Get-GitChangedFiles](https://github.com/genXdev/GenXdev.Coding/tree/main#get-gitchangedfiles) | gitchanged | Get the list of changed files in a Git repository. |
| [Get-ModuleHelpMarkdown](https://github.com/genXdev/GenXdev.Coding/tree/main#get-modulehelpmarkdown) | &nbsp; | &nbsp; |
| [Get-Refactor](https://github.com/genXdev/GenXdev.Coding/tree/main#get-refactor) | refactors | &nbsp; |
| [Get-RefactorReport](https://github.com/genXdev/GenXdev.Coding/tree/main#get-refactorreport) | refactorreport | Generates a detailed report of refactoring operations and their status. |
| [Ideas](https://github.com/genXdev/GenXdev.Coding/tree/main#ideas) | &nbsp; | &nbsp; |
| [Invoke-GenXdevPSFormatter](https://github.com/genXdev/GenXdev.Coding/tree/main#invoke-genxdevpsformatter) | &nbsp; | &nbsp; |
| [Invoke-GenXdevScriptAnalyzer](https://github.com/genXdev/GenXdev.Coding/tree/main#invoke-genxdevscriptanalyzer) | &nbsp; | &nbsp; |
| [Issues](https://github.com/genXdev/GenXdev.Coding/tree/main#issues) | &nbsp; | &nbsp; |
| [New-GenXdevCmdlet](https://github.com/genXdev/GenXdev.Coding/tree/main#new-genxdevcmdlet) | newcmd | Creates a new GenXdev PowerShell cmdlet with proper structure and validation. |
| [New-GenXdevModule](https://github.com/genXdev/GenXdev.Coding/tree/main#new-genxdevmodule) | &nbsp; | &nbsp; |
| [New-GitCommit](https://github.com/genXdev/GenXdev.Coding/tree/main#new-gitcommit) | commit | Creates and pushes a new git commit with all changes. |
| [New-PullRequestForGenXdevModuleChanges](https://github.com/genXdev/GenXdev.Coding/tree/main#new-pullrequestforgenxdevmodulechanges) | prgenxdevmodule | Creates a pull request for changes made to a GenXdev module. |
| [New-Refactor](https://github.com/genXdev/GenXdev.Coding/tree/main#new-refactor) | newrefactor | &nbsp; |
| [Open-GenXdevCmdletsContainingClipboardTextInIde](https://github.com/genXdev/GenXdev.Coding/tree/main#open-genxdevcmdletscontainingclipboardtextinide) | vscodesearch | Opens files in IDE that contain clipboard text |
| [Open-SourceFileInIde](https://github.com/genXdev/GenXdev.Coding/tree/main#open-sourcefileinide) | editcode | &nbsp; |
| [PermanentlyDeleteGitFolders](https://github.com/genXdev/GenXdev.Coding/tree/main#permanentlydeletegitfolders) | &nbsp; | Permanently deletes specified folders from all branches in a Git repository. |
| [ReleaseNotes](https://github.com/genXdev/GenXdev.Coding/tree/main#releasenotes) | &nbsp; | &nbsp; |
| [Remove-Refactor](https://github.com/genXdev/GenXdev.Coding/tree/main#remove-refactor) | &nbsp; | Removes refactor sets from GenXdev preferences system. |
| [Search-GenXdevCmdlet](https://github.com/genXdev/GenXdev.Coding/tree/main#search-genxdevcmdlet) | searchcmdlet | Searches for a GenXdev cmdlet and optionally opens it in an IDE for editing. |
| [Show-GenXdevCmdLetInIde](https://github.com/genXdev/GenXdev.Coding/tree/main#show-genxdevcmdletinide) | cmdlet, editcmdlet | Opens the specified GenXdev cmdlet in Visual Studio Code. |
| [SplitUpPsm1File](https://github.com/genXdev/GenXdev.Coding/tree/main#splituppsm1file) | &nbsp; | &nbsp; |
| [Start-NextRefactor](https://github.com/genXdev/GenXdev.Coding/tree/main#start-nextrefactor) | nextrefactor | &nbsp; |
| [Test-RefactorLLMSelection](https://github.com/genXdev/GenXdev.Coding/tree/main#test-refactorllmselection) | &nbsp; | Evaluates source files for refactoring eligibility using LLM analysis. |
| [Todoos](https://github.com/genXdev/GenXdev.Coding/tree/main#todoos) | &nbsp; | &nbsp; |
| [Update-Refactor](https://github.com/genXdev/GenXdev.Coding/tree/main#update-refactor) | updaterefactor | &nbsp; |
| [VSCode](https://github.com/genXdev/GenXdev.Coding/tree/main#vscode) | &nbsp; | &nbsp; |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Console

**A Windows PowerShell module for enhancing the commandline experience**

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [Add-SpotifyNewPlaylist](https://github.com/genXdev/GenXdev.Console/tree/main#add-spotifynewplaylist) | newplaylist | Creates a new Spotify playlist with customizable settings. |
| [Add-SpotifyTracksToLiked](https://github.com/genXdev/GenXdev.Console/tree/main#add-spotifytrackstoliked) | like | Adds tracks to the user's Spotify liked songs library. |
| [Add-SpotifyTracksToPlaylist](https://github.com/genXdev/GenXdev.Console/tree/main#add-spotifytrackstoplaylist) | addtoplaylist | Adds tracks to a Spotify playlist. |
| [Connect-SpotifyApiToken](https://github.com/genXdev/GenXdev.Console/tree/main#connect-spotifyapitoken) | &nbsp; | Authenticates with Spotify API using OAuth flow to obtain an access token. |
| [Enable-Screensaver](https://github.com/genXdev/GenXdev.Console/tree/main#enable-screensaver) | &nbsp; | &nbsp; |
| [Get-IsSpeaking](https://github.com/genXdev/GenXdev.Console/tree/main#get-isspeaking) | iss | Returns true if the text-to-speech engine is speaking. |
| [Get-SpotifyActiveDevice](https://github.com/genXdev/GenXdev.Console/tree/main#get-spotifyactivedevice) | &nbsp; | Returns all currently active Spotify devices for the current user. |
| [Get-SpotifyApiToken](https://github.com/genXdev/GenXdev.Console/tree/main#get-spotifyapitoken) | &nbsp; | Retrieves or generates a valid Spotify API authentication token. |
| [Get-SpotifyCurrentlyPlaying](https://github.com/genXdev/GenXdev.Console/tree/main#get-spotifycurrentlyplaying) | gcp | Returns information about the currently playing track on Spotify. |
| [Get-SpotifyDevice](https://github.com/genXdev/GenXdev.Console/tree/main#get-spotifydevice) | &nbsp; | Returns all currently available Spotify devices for current user. |
| [Get-SpotifyLikedTrack](https://github.com/genXdev/GenXdev.Console/tree/main#get-spotifylikedtrack) | liked | Retrieves all tracks saved in the user's Spotify Library. |
| [Get-SpotifyLyrics](https://github.com/genXdev/GenXdev.Console/tree/main#get-spotifylyrics) | lyrics | Retrieves lyrics for Spotify tracks from Musixmatch.com |
| [Get-SpotifyPlaylistIdsByName](https://github.com/genXdev/GenXdev.Console/tree/main#get-spotifyplaylistidsbyname) | &nbsp; | Retrieves Spotify playlist IDs by their names. |
| [Get-SpotifyPlaylistTrack](https://github.com/genXdev/GenXdev.Console/tree/main#get-spotifyplaylisttrack) | getplaylist | Returns all tracks from a Spotify playlist. |
| [Get-SpotifyTrackAudioFeatures](https://github.com/genXdev/GenXdev.Console/tree/main#get-spotifytrackaudiofeatures) | audiofeatures | Retrieves audio feature information for one or more Spotify tracks. |
| [Get-SpotifyTrackById](https://github.com/genXdev/GenXdev.Console/tree/main#get-spotifytrackbyid) | gettrack | Retrieves detailed track information from Spotify using a track ID. |
| [Get-SpotifyUserPlaylists](https://github.com/genXdev/GenXdev.Console/tree/main#get-spotifyuserplaylists) | gupl | Returns a collection of Spotify playlists owned by the current user. |
| [Move-SpotifyLikedTracksToPlaylist](https://github.com/genXdev/GenXdev.Console/tree/main#move-spotifylikedtrackstoplaylist) | moveliked | Moves all liked tracks from your Spotify library to specified playlist(s) |
| [New-MicrosoftShellTab](https://github.com/genXdev/GenXdev.Console/tree/main#new-microsoftshelltab) | x | &nbsp; |
| [Now](https://github.com/genXdev/GenXdev.Console/tree/main#now) | &nbsp; | Returns the current system date and time as a DateTime object. |
| [Open-MediaFile](https://github.com/genXdev/GenXdev.Console/tree/main#open-mediafile) | findmedia, media, vlcmedia | &nbsp; |
| [Open-VlcMediaPlayer](https://github.com/genXdev/GenXdev.Console/tree/main#open-vlcmediaplayer) | vlc | &nbsp; |
| [Open-VlcMediaPlayerLyrics](https://github.com/genXdev/GenXdev.Console/tree/main#open-vlcmediaplayerlyrics) | vlclyrics | &nbsp; |
| [Remove-SpotifyTracksFromLiked](https://github.com/genXdev/GenXdev.Console/tree/main#remove-spotifytracksfromliked) | dislike | Removes tracks from the user's Spotify Library (Liked Songs). |
| [Remove-SpotifyTracksFromPlaylist](https://github.com/genXdev/GenXdev.Console/tree/main#remove-spotifytracksfromplaylist) | removefromplaylist | Removes tracks from a Spotify playlist. |
| [SayDate](https://github.com/genXdev/GenXdev.Console/tree/main#saydate) | &nbsp; | &nbsp; |
| [SayTime](https://github.com/genXdev/GenXdev.Console/tree/main#saytime) | &nbsp; | Announces the current time using text-to-speech. |
| [Search-Spotify](https://github.com/genXdev/GenXdev.Console/tree/main#search-spotify) | fm, sm | Performs a Spotify search and returns matching items. |
| [Search-SpotifyAndEnqueue](https://github.com/genXdev/GenXdev.Console/tree/main#search-spotifyandenqueue) | fmq, smq | Searches Spotify and adds the first matching item to the playback queue. |
| [Search-SpotifyAndPlay](https://github.com/genXdev/GenXdev.Console/tree/main#search-spotifyandplay) | fmp, smp | Performs a Spotify search and plays the first found item. |
| [Set-MonitorPowerOff](https://github.com/genXdev/GenXdev.Console/tree/main#set-monitorpoweroff) | poweroff | Turns off power to all connected monitors. |
| [Set-MonitorPowerOn](https://github.com/genXdev/GenXdev.Console/tree/main#set-monitorpoweron) | monitoroff, wakemonitor | Turns the monitor power on. |
| [Set-SpotifyActiveDevice](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyactivedevice) | &nbsp; | Sets the active Spotify playback device. |
| [Set-SpotifyApiToken](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyapitoken) | &nbsp; | Caches a Spotify API token for later use in the local configuration. |
| [Set-SpotifyNext](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifynext) | next, skip | Skips to next track on Spotify. |
| [Set-SpotifyPause](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifypause) | pausemusic, togglepausemusic | Pauses Spotify playback |
| [Set-SpotifyPlaylistDetails](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyplaylistdetails) | spld | Sets the main properties of a Spotify playlist. |
| [Set-SpotifyPlaylistOrder](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyplaylistorder) | &nbsp; | Reorders tracks within a Spotify playlist by moving a range of items to a new position. |
| [Set-SpotifyPrevious](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyprevious) | prev, previous | Skips to the previous track in Spotify playback. |
| [Set-SpotifyRepeatContext](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyrepeatcontext) | repeat | Enables playlist repeat mode for Spotify playback. |
| [Set-SpotifyRepeatOff](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyrepeatoff) | norepeat, repeatoff | Disables Spotify repeat mode for the currently active device. |
| [Set-SpotifyRepeatSong](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyrepeatsong) | repeatsong | Enables song repeat mode in Spotify. |
| [Set-SpotifyShuffleOff](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyshuffleoff) | &nbsp; | Disables Spotify song-shuffle mode on the active device. |
| [Set-SpotifyShuffleOn](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyshuffleon) | shuffle, shuffleon | Enables Spotify song-shuffle mode. |
| [Set-SpotifyStart](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifystart) | play, startmusic | Starts Spotify playback on the currently active device. |
| [Set-SpotifyStop](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifystop) | stop | Stops Spotify playback on the active device. |
| [Set-TextToSpeechStopped](https://github.com/genXdev/GenXdev.Console/tree/main#set-texttospeechstopped) | Set-TextToSpeechStopped, sst | Immediately stops any ongoing text-to-speech output. |
| [Set-VLCPlayerFocused](https://github.com/genXdev/GenXdev.Console/tree/main#set-vlcplayerfocused) | fvlc, showvlc, vlcf | Sets focus to the VLC media player window. |
| [Start-SnakeGame](https://github.com/genXdev/GenXdev.Console/tree/main#start-snakegame) | snake | &nbsp; |
| [Start-TextToSpeech](https://github.com/genXdev/GenXdev.Console/tree/main#start-texttospeech) | say | Converts text to speech using the Windows Speech API. |
| [Start-VlcMediaPlayerNextInPlaylist](https://github.com/genXdev/GenXdev.Console/tree/main#start-vlcmediaplayernextinplaylist) | vlcnext | Advances VLC Media Player to the next item in the current playlist. |
| [Start-VlcMediaPlayerPreviousInPlaylist](https://github.com/genXdev/GenXdev.Console/tree/main#start-vlcmediaplayerpreviousinplaylist) | vlcback, vlcprev | Moves to the previous item in the VLC Media Player playlist. |
| [Switch-VlcMediaPlayerMute](https://github.com/genXdev/GenXdev.Console/tree/main#switch-vlcmediaplayermute) | vlcmute, vlcunmute | Toggles the mute state of the VLC Media Player. |
| [Switch-VLCMediaPlayerPaused](https://github.com/genXdev/GenXdev.Console/tree/main#switch-vlcmediaplayerpaused) | vlcpause, vlcplay | Toggles the pause/play state of the VLC Media Player. |
| [Switch-VlcMediaPlayerRepeat](https://github.com/genXdev/GenXdev.Console/tree/main#switch-vlcmediaplayerrepeat) | vlcrepeat | Toggles the repeat mode in VLC Media Player. |
| [UtcNow](https://github.com/genXdev/GenXdev.Console/tree/main#utcnow) | &nbsp; | Gets the current UTC (Coordinated Universal Time) date and time. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Console/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Console.Spotify

**A Windows PowerShell module for enhancing the commandline experience**

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [Add-SpotifyNewPlaylist](https://github.com/genXdev/GenXdev.Console/tree/main#add-spotifynewplaylist) | newplaylist | Creates a new Spotify playlist with customizable settings. |
| [Add-SpotifyTracksToLiked](https://github.com/genXdev/GenXdev.Console/tree/main#add-spotifytrackstoliked) | like | Adds tracks to the user's Spotify liked songs library. |
| [Add-SpotifyTracksToPlaylist](https://github.com/genXdev/GenXdev.Console/tree/main#add-spotifytrackstoplaylist) | addtoplaylist | Adds tracks to a Spotify playlist. |
| [Connect-SpotifyApiToken](https://github.com/genXdev/GenXdev.Console/tree/main#connect-spotifyapitoken) | &nbsp; | Authenticates with Spotify API using OAuth flow to obtain an access token. |
| [Enable-Screensaver](https://github.com/genXdev/GenXdev.Console/tree/main#enable-screensaver) | &nbsp; | &nbsp; |
| [Get-IsSpeaking](https://github.com/genXdev/GenXdev.Console/tree/main#get-isspeaking) | iss | Returns true if the text-to-speech engine is speaking. |
| [Get-SpotifyActiveDevice](https://github.com/genXdev/GenXdev.Console/tree/main#get-spotifyactivedevice) | &nbsp; | Returns all currently active Spotify devices for the current user. |
| [Get-SpotifyApiToken](https://github.com/genXdev/GenXdev.Console/tree/main#get-spotifyapitoken) | &nbsp; | Retrieves or generates a valid Spotify API authentication token. |
| [Get-SpotifyCurrentlyPlaying](https://github.com/genXdev/GenXdev.Console/tree/main#get-spotifycurrentlyplaying) | gcp | Returns information about the currently playing track on Spotify. |
| [Get-SpotifyDevice](https://github.com/genXdev/GenXdev.Console/tree/main#get-spotifydevice) | &nbsp; | Returns all currently available Spotify devices for current user. |
| [Get-SpotifyLikedTrack](https://github.com/genXdev/GenXdev.Console/tree/main#get-spotifylikedtrack) | liked | Retrieves all tracks saved in the user's Spotify Library. |
| [Get-SpotifyLyrics](https://github.com/genXdev/GenXdev.Console/tree/main#get-spotifylyrics) | lyrics | Retrieves lyrics for Spotify tracks from Musixmatch.com |
| [Get-SpotifyPlaylistIdsByName](https://github.com/genXdev/GenXdev.Console/tree/main#get-spotifyplaylistidsbyname) | &nbsp; | Retrieves Spotify playlist IDs by their names. |
| [Get-SpotifyPlaylistTrack](https://github.com/genXdev/GenXdev.Console/tree/main#get-spotifyplaylisttrack) | getplaylist | Returns all tracks from a Spotify playlist. |
| [Get-SpotifyTrackAudioFeatures](https://github.com/genXdev/GenXdev.Console/tree/main#get-spotifytrackaudiofeatures) | audiofeatures | Retrieves audio feature information for one or more Spotify tracks. |
| [Get-SpotifyTrackById](https://github.com/genXdev/GenXdev.Console/tree/main#get-spotifytrackbyid) | gettrack | Retrieves detailed track information from Spotify using a track ID. |
| [Get-SpotifyUserPlaylists](https://github.com/genXdev/GenXdev.Console/tree/main#get-spotifyuserplaylists) | gupl | Returns a collection of Spotify playlists owned by the current user. |
| [Move-SpotifyLikedTracksToPlaylist](https://github.com/genXdev/GenXdev.Console/tree/main#move-spotifylikedtrackstoplaylist) | moveliked | Moves all liked tracks from your Spotify library to specified playlist(s) |
| [New-MicrosoftShellTab](https://github.com/genXdev/GenXdev.Console/tree/main#new-microsoftshelltab) | x | &nbsp; |
| [Now](https://github.com/genXdev/GenXdev.Console/tree/main#now) | &nbsp; | Returns the current system date and time as a DateTime object. |
| [Open-MediaFile](https://github.com/genXdev/GenXdev.Console/tree/main#open-mediafile) | findmedia, media, vlcmedia | &nbsp; |
| [Open-VlcMediaPlayer](https://github.com/genXdev/GenXdev.Console/tree/main#open-vlcmediaplayer) | vlc | &nbsp; |
| [Open-VlcMediaPlayerLyrics](https://github.com/genXdev/GenXdev.Console/tree/main#open-vlcmediaplayerlyrics) | vlclyrics | &nbsp; |
| [Remove-SpotifyTracksFromLiked](https://github.com/genXdev/GenXdev.Console/tree/main#remove-spotifytracksfromliked) | dislike | Removes tracks from the user's Spotify Library (Liked Songs). |
| [Remove-SpotifyTracksFromPlaylist](https://github.com/genXdev/GenXdev.Console/tree/main#remove-spotifytracksfromplaylist) | removefromplaylist | Removes tracks from a Spotify playlist. |
| [SayDate](https://github.com/genXdev/GenXdev.Console/tree/main#saydate) | &nbsp; | &nbsp; |
| [SayTime](https://github.com/genXdev/GenXdev.Console/tree/main#saytime) | &nbsp; | Announces the current time using text-to-speech. |
| [Search-Spotify](https://github.com/genXdev/GenXdev.Console/tree/main#search-spotify) | fm, sm | Performs a Spotify search and returns matching items. |
| [Search-SpotifyAndEnqueue](https://github.com/genXdev/GenXdev.Console/tree/main#search-spotifyandenqueue) | fmq, smq | Searches Spotify and adds the first matching item to the playback queue. |
| [Search-SpotifyAndPlay](https://github.com/genXdev/GenXdev.Console/tree/main#search-spotifyandplay) | fmp, smp | Performs a Spotify search and plays the first found item. |
| [Set-MonitorPowerOff](https://github.com/genXdev/GenXdev.Console/tree/main#set-monitorpoweroff) | poweroff | Turns off power to all connected monitors. |
| [Set-MonitorPowerOn](https://github.com/genXdev/GenXdev.Console/tree/main#set-monitorpoweron) | monitoroff, wakemonitor | Turns the monitor power on. |
| [Set-SpotifyActiveDevice](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyactivedevice) | &nbsp; | Sets the active Spotify playback device. |
| [Set-SpotifyApiToken](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyapitoken) | &nbsp; | Caches a Spotify API token for later use in the local configuration. |
| [Set-SpotifyNext](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifynext) | next, skip | Skips to next track on Spotify. |
| [Set-SpotifyPause](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifypause) | pausemusic, togglepausemusic | Pauses Spotify playback |
| [Set-SpotifyPlaylistDetails](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyplaylistdetails) | spld | Sets the main properties of a Spotify playlist. |
| [Set-SpotifyPlaylistOrder](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyplaylistorder) | &nbsp; | Reorders tracks within a Spotify playlist by moving a range of items to a new position. |
| [Set-SpotifyPrevious](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyprevious) | prev, previous | Skips to the previous track in Spotify playback. |
| [Set-SpotifyRepeatContext](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyrepeatcontext) | repeat | Enables playlist repeat mode for Spotify playback. |
| [Set-SpotifyRepeatOff](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyrepeatoff) | norepeat, repeatoff | Disables Spotify repeat mode for the currently active device. |
| [Set-SpotifyRepeatSong](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyrepeatsong) | repeatsong | Enables song repeat mode in Spotify. |
| [Set-SpotifyShuffleOff](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyshuffleoff) | &nbsp; | Disables Spotify song-shuffle mode on the active device. |
| [Set-SpotifyShuffleOn](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyshuffleon) | shuffle, shuffleon | Enables Spotify song-shuffle mode. |
| [Set-SpotifyStart](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifystart) | play, startmusic | Starts Spotify playback on the currently active device. |
| [Set-SpotifyStop](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifystop) | stop | Stops Spotify playback on the active device. |
| [Set-TextToSpeechStopped](https://github.com/genXdev/GenXdev.Console/tree/main#set-texttospeechstopped) | Set-TextToSpeechStopped, sst | Immediately stops any ongoing text-to-speech output. |
| [Set-VLCPlayerFocused](https://github.com/genXdev/GenXdev.Console/tree/main#set-vlcplayerfocused) | fvlc, showvlc, vlcf | Sets focus to the VLC media player window. |
| [Start-SnakeGame](https://github.com/genXdev/GenXdev.Console/tree/main#start-snakegame) | snake | &nbsp; |
| [Start-TextToSpeech](https://github.com/genXdev/GenXdev.Console/tree/main#start-texttospeech) | say | Converts text to speech using the Windows Speech API. |
| [Start-VlcMediaPlayerNextInPlaylist](https://github.com/genXdev/GenXdev.Console/tree/main#start-vlcmediaplayernextinplaylist) | vlcnext | Advances VLC Media Player to the next item in the current playlist. |
| [Start-VlcMediaPlayerPreviousInPlaylist](https://github.com/genXdev/GenXdev.Console/tree/main#start-vlcmediaplayerpreviousinplaylist) | vlcback, vlcprev | Moves to the previous item in the VLC Media Player playlist. |
| [Switch-VlcMediaPlayerMute](https://github.com/genXdev/GenXdev.Console/tree/main#switch-vlcmediaplayermute) | vlcmute, vlcunmute | Toggles the mute state of the VLC Media Player. |
| [Switch-VLCMediaPlayerPaused](https://github.com/genXdev/GenXdev.Console/tree/main#switch-vlcmediaplayerpaused) | vlcpause, vlcplay | Toggles the pause/play state of the VLC Media Player. |
| [Switch-VlcMediaPlayerRepeat](https://github.com/genXdev/GenXdev.Console/tree/main#switch-vlcmediaplayerrepeat) | vlcrepeat | Toggles the repeat mode in VLC Media Player. |
| [UtcNow](https://github.com/genXdev/GenXdev.Console/tree/main#utcnow) | &nbsp; | Gets the current UTC (Coordinated Universal Time) date and time. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Console/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Console.Vlc

**A Windows PowerShell module for enhancing the commandline experience**

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [Add-SpotifyNewPlaylist](https://github.com/genXdev/GenXdev.Console/tree/main#add-spotifynewplaylist) | newplaylist | Creates a new Spotify playlist with customizable settings. |
| [Add-SpotifyTracksToLiked](https://github.com/genXdev/GenXdev.Console/tree/main#add-spotifytrackstoliked) | like | Adds tracks to the user's Spotify liked songs library. |
| [Add-SpotifyTracksToPlaylist](https://github.com/genXdev/GenXdev.Console/tree/main#add-spotifytrackstoplaylist) | addtoplaylist | Adds tracks to a Spotify playlist. |
| [Connect-SpotifyApiToken](https://github.com/genXdev/GenXdev.Console/tree/main#connect-spotifyapitoken) | &nbsp; | Authenticates with Spotify API using OAuth flow to obtain an access token. |
| [Enable-Screensaver](https://github.com/genXdev/GenXdev.Console/tree/main#enable-screensaver) | &nbsp; | &nbsp; |
| [Get-IsSpeaking](https://github.com/genXdev/GenXdev.Console/tree/main#get-isspeaking) | iss | Returns true if the text-to-speech engine is speaking. |
| [Get-SpotifyActiveDevice](https://github.com/genXdev/GenXdev.Console/tree/main#get-spotifyactivedevice) | &nbsp; | Returns all currently active Spotify devices for the current user. |
| [Get-SpotifyApiToken](https://github.com/genXdev/GenXdev.Console/tree/main#get-spotifyapitoken) | &nbsp; | Retrieves or generates a valid Spotify API authentication token. |
| [Get-SpotifyCurrentlyPlaying](https://github.com/genXdev/GenXdev.Console/tree/main#get-spotifycurrentlyplaying) | gcp | Returns information about the currently playing track on Spotify. |
| [Get-SpotifyDevice](https://github.com/genXdev/GenXdev.Console/tree/main#get-spotifydevice) | &nbsp; | Returns all currently available Spotify devices for current user. |
| [Get-SpotifyLikedTrack](https://github.com/genXdev/GenXdev.Console/tree/main#get-spotifylikedtrack) | liked | Retrieves all tracks saved in the user's Spotify Library. |
| [Get-SpotifyLyrics](https://github.com/genXdev/GenXdev.Console/tree/main#get-spotifylyrics) | lyrics | Retrieves lyrics for Spotify tracks from Musixmatch.com |
| [Get-SpotifyPlaylistIdsByName](https://github.com/genXdev/GenXdev.Console/tree/main#get-spotifyplaylistidsbyname) | &nbsp; | Retrieves Spotify playlist IDs by their names. |
| [Get-SpotifyPlaylistTrack](https://github.com/genXdev/GenXdev.Console/tree/main#get-spotifyplaylisttrack) | getplaylist | Returns all tracks from a Spotify playlist. |
| [Get-SpotifyTrackAudioFeatures](https://github.com/genXdev/GenXdev.Console/tree/main#get-spotifytrackaudiofeatures) | audiofeatures | Retrieves audio feature information for one or more Spotify tracks. |
| [Get-SpotifyTrackById](https://github.com/genXdev/GenXdev.Console/tree/main#get-spotifytrackbyid) | gettrack | Retrieves detailed track information from Spotify using a track ID. |
| [Get-SpotifyUserPlaylists](https://github.com/genXdev/GenXdev.Console/tree/main#get-spotifyuserplaylists) | gupl | Returns a collection of Spotify playlists owned by the current user. |
| [Move-SpotifyLikedTracksToPlaylist](https://github.com/genXdev/GenXdev.Console/tree/main#move-spotifylikedtrackstoplaylist) | moveliked | Moves all liked tracks from your Spotify library to specified playlist(s) |
| [New-MicrosoftShellTab](https://github.com/genXdev/GenXdev.Console/tree/main#new-microsoftshelltab) | x | &nbsp; |
| [Now](https://github.com/genXdev/GenXdev.Console/tree/main#now) | &nbsp; | Returns the current system date and time as a DateTime object. |
| [Open-MediaFile](https://github.com/genXdev/GenXdev.Console/tree/main#open-mediafile) | findmedia, media, vlcmedia | &nbsp; |
| [Open-VlcMediaPlayer](https://github.com/genXdev/GenXdev.Console/tree/main#open-vlcmediaplayer) | vlc | &nbsp; |
| [Open-VlcMediaPlayerLyrics](https://github.com/genXdev/GenXdev.Console/tree/main#open-vlcmediaplayerlyrics) | vlclyrics | &nbsp; |
| [Remove-SpotifyTracksFromLiked](https://github.com/genXdev/GenXdev.Console/tree/main#remove-spotifytracksfromliked) | dislike | Removes tracks from the user's Spotify Library (Liked Songs). |
| [Remove-SpotifyTracksFromPlaylist](https://github.com/genXdev/GenXdev.Console/tree/main#remove-spotifytracksfromplaylist) | removefromplaylist | Removes tracks from a Spotify playlist. |
| [SayDate](https://github.com/genXdev/GenXdev.Console/tree/main#saydate) | &nbsp; | &nbsp; |
| [SayTime](https://github.com/genXdev/GenXdev.Console/tree/main#saytime) | &nbsp; | Announces the current time using text-to-speech. |
| [Search-Spotify](https://github.com/genXdev/GenXdev.Console/tree/main#search-spotify) | fm, sm | Performs a Spotify search and returns matching items. |
| [Search-SpotifyAndEnqueue](https://github.com/genXdev/GenXdev.Console/tree/main#search-spotifyandenqueue) | fmq, smq | Searches Spotify and adds the first matching item to the playback queue. |
| [Search-SpotifyAndPlay](https://github.com/genXdev/GenXdev.Console/tree/main#search-spotifyandplay) | fmp, smp | Performs a Spotify search and plays the first found item. |
| [Set-MonitorPowerOff](https://github.com/genXdev/GenXdev.Console/tree/main#set-monitorpoweroff) | poweroff | Turns off power to all connected monitors. |
| [Set-MonitorPowerOn](https://github.com/genXdev/GenXdev.Console/tree/main#set-monitorpoweron) | monitoroff, wakemonitor | Turns the monitor power on. |
| [Set-SpotifyActiveDevice](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyactivedevice) | &nbsp; | Sets the active Spotify playback device. |
| [Set-SpotifyApiToken](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyapitoken) | &nbsp; | Caches a Spotify API token for later use in the local configuration. |
| [Set-SpotifyNext](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifynext) | next, skip | Skips to next track on Spotify. |
| [Set-SpotifyPause](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifypause) | pausemusic, togglepausemusic | Pauses Spotify playback |
| [Set-SpotifyPlaylistDetails](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyplaylistdetails) | spld | Sets the main properties of a Spotify playlist. |
| [Set-SpotifyPlaylistOrder](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyplaylistorder) | &nbsp; | Reorders tracks within a Spotify playlist by moving a range of items to a new position. |
| [Set-SpotifyPrevious](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyprevious) | prev, previous | Skips to the previous track in Spotify playback. |
| [Set-SpotifyRepeatContext](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyrepeatcontext) | repeat | Enables playlist repeat mode for Spotify playback. |
| [Set-SpotifyRepeatOff](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyrepeatoff) | norepeat, repeatoff | Disables Spotify repeat mode for the currently active device. |
| [Set-SpotifyRepeatSong](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyrepeatsong) | repeatsong | Enables song repeat mode in Spotify. |
| [Set-SpotifyShuffleOff](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyshuffleoff) | &nbsp; | Disables Spotify song-shuffle mode on the active device. |
| [Set-SpotifyShuffleOn](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyshuffleon) | shuffle, shuffleon | Enables Spotify song-shuffle mode. |
| [Set-SpotifyStart](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifystart) | play, startmusic | Starts Spotify playback on the currently active device. |
| [Set-SpotifyStop](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifystop) | stop | Stops Spotify playback on the active device. |
| [Set-TextToSpeechStopped](https://github.com/genXdev/GenXdev.Console/tree/main#set-texttospeechstopped) | Set-TextToSpeechStopped, sst | Immediately stops any ongoing text-to-speech output. |
| [Set-VLCPlayerFocused](https://github.com/genXdev/GenXdev.Console/tree/main#set-vlcplayerfocused) | fvlc, showvlc, vlcf | Sets focus to the VLC media player window. |
| [Start-SnakeGame](https://github.com/genXdev/GenXdev.Console/tree/main#start-snakegame) | snake | &nbsp; |
| [Start-TextToSpeech](https://github.com/genXdev/GenXdev.Console/tree/main#start-texttospeech) | say | Converts text to speech using the Windows Speech API. |
| [Start-VlcMediaPlayerNextInPlaylist](https://github.com/genXdev/GenXdev.Console/tree/main#start-vlcmediaplayernextinplaylist) | vlcnext | Advances VLC Media Player to the next item in the current playlist. |
| [Start-VlcMediaPlayerPreviousInPlaylist](https://github.com/genXdev/GenXdev.Console/tree/main#start-vlcmediaplayerpreviousinplaylist) | vlcback, vlcprev | Moves to the previous item in the VLC Media Player playlist. |
| [Switch-VlcMediaPlayerMute](https://github.com/genXdev/GenXdev.Console/tree/main#switch-vlcmediaplayermute) | vlcmute, vlcunmute | Toggles the mute state of the VLC Media Player. |
| [Switch-VLCMediaPlayerPaused](https://github.com/genXdev/GenXdev.Console/tree/main#switch-vlcmediaplayerpaused) | vlcpause, vlcplay | Toggles the pause/play state of the VLC Media Player. |
| [Switch-VlcMediaPlayerRepeat](https://github.com/genXdev/GenXdev.Console/tree/main#switch-vlcmediaplayerrepeat) | vlcrepeat | Toggles the repeat mode in VLC Media Player. |
| [UtcNow](https://github.com/genXdev/GenXdev.Console/tree/main#utcnow) | &nbsp; | Gets the current UTC (Coordinated Universal Time) date and time. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Console/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Data

**A Windows PowerShell module for enhancing the commandline experience**

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [EnsureSQLiteStudioInstalled](https://github.com/genXdev/GenXdev.Data/tree/main#ensuresqlitestudioinstalled) | &nbsp; | &nbsp; |
| [EnsureSSMSInstalled](https://github.com/genXdev/GenXdev.Data/tree/main#ensuressmsinstalled) | &nbsp; | &nbsp; |
| [Get-GenXdevPreference](https://github.com/genXdev/GenXdev.Data/tree/main#get-genxdevpreference) | getPreference | Retrieves a preference value from the GenXdev preferences store. |
| [Get-GenXdevPreferenceNames](https://github.com/genXdev/GenXdev.Data/tree/main#get-genxdevpreferencenames) | getPreferenceNames | Gets all preference names from session storage and database stores. |
| [Get-GenXdevPreferencesDatabasePath](https://github.com/genXdev/GenXdev.Data/tree/main#get-genxdevpreferencesdatabasepath) | &nbsp; | Gets the configured database path for preference data files used in GenXdev.Data operations. |
| [Get-KeyValueStoreNames](https://github.com/genXdev/GenXdev.Data/tree/main#get-keyvaluestorenames) | getstorenames | Retrieves the names of available key-value stores. |
| [Get-KeyValueStorePath](https://github.com/genXdev/GenXdev.Data/tree/main#get-keyvaluestorepath) | &nbsp; | Gets the file path for a key-value store. |
| [Get-SQLiteSchema](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqliteschema) | &nbsp; | Retrieves the complete schema information from a SQLite database. |
| [Get-SQLiteTableColumnData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetablecolumndata) | &nbsp; | Retrieves data from a specific column in a SQLite database table. |
| [Get-SQLiteTableData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetabledata) | &nbsp; | Retrieves data from a SQLite database table with optional record limiting. |
| [Get-SQLiteTables](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetables) | &nbsp; | Retrieves a list of table names from a SQLite database. |
| [Get-SQLiteTableSchema](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetableschema) | &nbsp; | Retrieves the schema information for a specified SQLite table. |
| [Get-SQLiteTransaction](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetransaction) | &nbsp; | &nbsp; |
| [Get-SQLiteViewColumnData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqliteviewcolumndata) | &nbsp; | Retrieves column data from a SQLite view with optional record limiting. |
| [Get-SQLiteViewData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqliteviewdata) | &nbsp; | Retrieves data from a SQLite database view with optional record limiting. |
| [Get-SQLiteViews](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqliteviews) | &nbsp; | Retrieves a list of views from a SQLite database. |
| [Get-SQLiteViewSchema](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqliteviewschema) | &nbsp; | Retrieves the SQL schema definition for a SQLite view. |
| [Get-SQLServerSchema](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlserverschema) | &nbsp; | Retrieves the complete schema information from a SQL Server database. |
| [Get-SQLServerTableColumnData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlservertablecolumndata) | &nbsp; | Retrieves data from a specific column in a SQL database table. |
| [Get-SQLServerTableData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlservertabledata) | &nbsp; | Retrieves data from a SQL database table with optional record limiting. |
| [Get-SQLServerTables](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlservertables) | &nbsp; | Retrieves a list of table names from a SQL Server database. |
| [Get-SQLServerTableSchema](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlservertableschema) | &nbsp; | Retrieves the schema information for a specified SQL Server table. |
| [Get-SQLServerTransaction](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlservertransaction) | getsqltx, newsqltx | Creates and returns a SQL Server transaction object for batch operations. |
| [Get-SQLServerViewColumnData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlserverviewcolumndata) | &nbsp; | Retrieves column data from a SQL view with optional record limiting. |
| [Get-SQLServerViewData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlserverviewdata) | &nbsp; | Retrieves data from a SQL database view with optional record limiting. |
| [Get-SQLServerViews](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlserverviews) | &nbsp; | Retrieves a list of views from a SQL Server database. |
| [Get-SQLServerViewSchema](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlserverviewschema) | &nbsp; | Retrieves the SQL schema definition for a SQL Server view. |
| [Get-StoreKeys](https://github.com/genXdev/GenXdev.Data/tree/main#get-storekeys) | getkeys | Retrieves all key names for a given key-value store. |
| [Get-ValueByKeyFromStore](https://github.com/genXdev/GenXdev.Data/tree/main#get-valuebykeyfromstore) | getvalue | Retrieves a value from a JSON-based key-value store. |
| [Initialize-KeyValueStores](https://github.com/genXdev/GenXdev.Data/tree/main#initialize-keyvaluestores) | &nbsp; | Initializes KeyValueStore directory structure for local and OneDrive storage. |
| [Invoke-SQLiteQuery](https://github.com/genXdev/GenXdev.Data/tree/main#invoke-sqlitequery) | &nbsp; | &nbsp; |
| [Invoke-SQLiteStudio](https://github.com/genXdev/GenXdev.Data/tree/main#invoke-sqlitestudio) | &nbsp; | Executes SQLite database queries with support for parameters and transactions. |
| [Invoke-SqlServerQuery](https://github.com/genXdev/GenXdev.Data/tree/main#invoke-sqlserverquery) | &nbsp; | &nbsp; |
| [Invoke-SSMS](https://github.com/genXdev/GenXdev.Data/tree/main#invoke-ssms) | sqlservermanagementstudio, ssms | Launches SQL Server Management Studio (SSMS) after ensuring it is installed. |
| [New-SQLiteDatabase](https://github.com/genXdev/GenXdev.Data/tree/main#new-sqlitedatabase) | &nbsp; | &nbsp; |
| [New-SQLServerDatabase](https://github.com/genXdev/GenXdev.Data/tree/main#new-sqlserverdatabase) | nsqldb | Creates a new SQL Server database. |
| [Remove-GenXdevPreference](https://github.com/genXdev/GenXdev.Data/tree/main#remove-genxdevpreference) | removePreference | Removes a preference value from the GenXdev preferences store. |
| [Remove-KeyFromStore](https://github.com/genXdev/GenXdev.Data/tree/main#remove-keyfromstore) | removekey | Removes a key from a key-value store. |
| [Remove-KeyValueStore](https://github.com/genXdev/GenXdev.Data/tree/main#remove-keyvaluestore) | &nbsp; | Removes a key-value store. |
| [Set-GenXdevDefaultPreference](https://github.com/genXdev/GenXdev.Data/tree/main#set-genxdevdefaultpreference) | setPreferenceDefault | Sets a default preference value in the GenXdev preferences store. |
| [Set-GenXdevPreference](https://github.com/genXdev/GenXdev.Data/tree/main#set-genxdevpreference) | setPreference | Sets a preference value in the GenXdev preferences store. |
| [Set-GenXdevPreferencesDatabasePath](https://github.com/genXdev/GenXdev.Data/tree/main#set-genxdevpreferencesdatabasepath) | &nbsp; | Sets the database path for preferences used in GenXdev.Data operations. |
| [Set-ValueByKeyInStore](https://github.com/genXdev/GenXdev.Data/tree/main#set-valuebykeyinstore) | setvalue | Manages key-value pairs in a JSON file-based store. |
| [Sync-KeyValueStore](https://github.com/genXdev/GenXdev.Data/tree/main#sync-keyvaluestore) | &nbsp; | Synchronizes local and OneDrive key-value store JSON files. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Data/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Data.KeyValueStore

**A Windows PowerShell module for enhancing the commandline experience**

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [EnsureSQLiteStudioInstalled](https://github.com/genXdev/GenXdev.Data/tree/main#ensuresqlitestudioinstalled) | &nbsp; | &nbsp; |
| [EnsureSSMSInstalled](https://github.com/genXdev/GenXdev.Data/tree/main#ensuressmsinstalled) | &nbsp; | &nbsp; |
| [Get-GenXdevPreference](https://github.com/genXdev/GenXdev.Data/tree/main#get-genxdevpreference) | getPreference | Retrieves a preference value from the GenXdev preferences store. |
| [Get-GenXdevPreferenceNames](https://github.com/genXdev/GenXdev.Data/tree/main#get-genxdevpreferencenames) | getPreferenceNames | Gets all preference names from session storage and database stores. |
| [Get-GenXdevPreferencesDatabasePath](https://github.com/genXdev/GenXdev.Data/tree/main#get-genxdevpreferencesdatabasepath) | &nbsp; | Gets the configured database path for preference data files used in GenXdev.Data operations. |
| [Get-KeyValueStoreNames](https://github.com/genXdev/GenXdev.Data/tree/main#get-keyvaluestorenames) | getstorenames | Retrieves the names of available key-value stores. |
| [Get-KeyValueStorePath](https://github.com/genXdev/GenXdev.Data/tree/main#get-keyvaluestorepath) | &nbsp; | Gets the file path for a key-value store. |
| [Get-SQLiteSchema](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqliteschema) | &nbsp; | Retrieves the complete schema information from a SQLite database. |
| [Get-SQLiteTableColumnData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetablecolumndata) | &nbsp; | Retrieves data from a specific column in a SQLite database table. |
| [Get-SQLiteTableData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetabledata) | &nbsp; | Retrieves data from a SQLite database table with optional record limiting. |
| [Get-SQLiteTables](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetables) | &nbsp; | Retrieves a list of table names from a SQLite database. |
| [Get-SQLiteTableSchema](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetableschema) | &nbsp; | Retrieves the schema information for a specified SQLite table. |
| [Get-SQLiteTransaction](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetransaction) | &nbsp; | &nbsp; |
| [Get-SQLiteViewColumnData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqliteviewcolumndata) | &nbsp; | Retrieves column data from a SQLite view with optional record limiting. |
| [Get-SQLiteViewData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqliteviewdata) | &nbsp; | Retrieves data from a SQLite database view with optional record limiting. |
| [Get-SQLiteViews](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqliteviews) | &nbsp; | Retrieves a list of views from a SQLite database. |
| [Get-SQLiteViewSchema](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqliteviewschema) | &nbsp; | Retrieves the SQL schema definition for a SQLite view. |
| [Get-SQLServerSchema](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlserverschema) | &nbsp; | Retrieves the complete schema information from a SQL Server database. |
| [Get-SQLServerTableColumnData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlservertablecolumndata) | &nbsp; | Retrieves data from a specific column in a SQL database table. |
| [Get-SQLServerTableData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlservertabledata) | &nbsp; | Retrieves data from a SQL database table with optional record limiting. |
| [Get-SQLServerTables](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlservertables) | &nbsp; | Retrieves a list of table names from a SQL Server database. |
| [Get-SQLServerTableSchema](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlservertableschema) | &nbsp; | Retrieves the schema information for a specified SQL Server table. |
| [Get-SQLServerTransaction](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlservertransaction) | getsqltx, newsqltx | Creates and returns a SQL Server transaction object for batch operations. |
| [Get-SQLServerViewColumnData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlserverviewcolumndata) | &nbsp; | Retrieves column data from a SQL view with optional record limiting. |
| [Get-SQLServerViewData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlserverviewdata) | &nbsp; | Retrieves data from a SQL database view with optional record limiting. |
| [Get-SQLServerViews](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlserverviews) | &nbsp; | Retrieves a list of views from a SQL Server database. |
| [Get-SQLServerViewSchema](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlserverviewschema) | &nbsp; | Retrieves the SQL schema definition for a SQL Server view. |
| [Get-StoreKeys](https://github.com/genXdev/GenXdev.Data/tree/main#get-storekeys) | getkeys | Retrieves all key names for a given key-value store. |
| [Get-ValueByKeyFromStore](https://github.com/genXdev/GenXdev.Data/tree/main#get-valuebykeyfromstore) | getvalue | Retrieves a value from a JSON-based key-value store. |
| [Initialize-KeyValueStores](https://github.com/genXdev/GenXdev.Data/tree/main#initialize-keyvaluestores) | &nbsp; | Initializes KeyValueStore directory structure for local and OneDrive storage. |
| [Invoke-SQLiteQuery](https://github.com/genXdev/GenXdev.Data/tree/main#invoke-sqlitequery) | &nbsp; | &nbsp; |
| [Invoke-SQLiteStudio](https://github.com/genXdev/GenXdev.Data/tree/main#invoke-sqlitestudio) | &nbsp; | Executes SQLite database queries with support for parameters and transactions. |
| [Invoke-SqlServerQuery](https://github.com/genXdev/GenXdev.Data/tree/main#invoke-sqlserverquery) | &nbsp; | &nbsp; |
| [Invoke-SSMS](https://github.com/genXdev/GenXdev.Data/tree/main#invoke-ssms) | sqlservermanagementstudio, ssms | Launches SQL Server Management Studio (SSMS) after ensuring it is installed. |
| [New-SQLiteDatabase](https://github.com/genXdev/GenXdev.Data/tree/main#new-sqlitedatabase) | &nbsp; | &nbsp; |
| [New-SQLServerDatabase](https://github.com/genXdev/GenXdev.Data/tree/main#new-sqlserverdatabase) | nsqldb | Creates a new SQL Server database. |
| [Remove-GenXdevPreference](https://github.com/genXdev/GenXdev.Data/tree/main#remove-genxdevpreference) | removePreference | Removes a preference value from the GenXdev preferences store. |
| [Remove-KeyFromStore](https://github.com/genXdev/GenXdev.Data/tree/main#remove-keyfromstore) | removekey | Removes a key from a key-value store. |
| [Remove-KeyValueStore](https://github.com/genXdev/GenXdev.Data/tree/main#remove-keyvaluestore) | &nbsp; | Removes a key-value store. |
| [Set-GenXdevDefaultPreference](https://github.com/genXdev/GenXdev.Data/tree/main#set-genxdevdefaultpreference) | setPreferenceDefault | Sets a default preference value in the GenXdev preferences store. |
| [Set-GenXdevPreference](https://github.com/genXdev/GenXdev.Data/tree/main#set-genxdevpreference) | setPreference | Sets a preference value in the GenXdev preferences store. |
| [Set-GenXdevPreferencesDatabasePath](https://github.com/genXdev/GenXdev.Data/tree/main#set-genxdevpreferencesdatabasepath) | &nbsp; | Sets the database path for preferences used in GenXdev.Data operations. |
| [Set-ValueByKeyInStore](https://github.com/genXdev/GenXdev.Data/tree/main#set-valuebykeyinstore) | setvalue | Manages key-value pairs in a JSON file-based store. |
| [Sync-KeyValueStore](https://github.com/genXdev/GenXdev.Data/tree/main#sync-keyvaluestore) | &nbsp; | Synchronizes local and OneDrive key-value store JSON files. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Data/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Data.Preferences

**A Windows PowerShell module for enhancing the commandline experience**

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [EnsureSQLiteStudioInstalled](https://github.com/genXdev/GenXdev.Data/tree/main#ensuresqlitestudioinstalled) | &nbsp; | &nbsp; |
| [EnsureSSMSInstalled](https://github.com/genXdev/GenXdev.Data/tree/main#ensuressmsinstalled) | &nbsp; | &nbsp; |
| [Get-GenXdevPreference](https://github.com/genXdev/GenXdev.Data/tree/main#get-genxdevpreference) | getPreference | Retrieves a preference value from the GenXdev preferences store. |
| [Get-GenXdevPreferenceNames](https://github.com/genXdev/GenXdev.Data/tree/main#get-genxdevpreferencenames) | getPreferenceNames | Gets all preference names from session storage and database stores. |
| [Get-GenXdevPreferencesDatabasePath](https://github.com/genXdev/GenXdev.Data/tree/main#get-genxdevpreferencesdatabasepath) | &nbsp; | Gets the configured database path for preference data files used in GenXdev.Data operations. |
| [Get-KeyValueStoreNames](https://github.com/genXdev/GenXdev.Data/tree/main#get-keyvaluestorenames) | getstorenames | Retrieves the names of available key-value stores. |
| [Get-KeyValueStorePath](https://github.com/genXdev/GenXdev.Data/tree/main#get-keyvaluestorepath) | &nbsp; | Gets the file path for a key-value store. |
| [Get-SQLiteSchema](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqliteschema) | &nbsp; | Retrieves the complete schema information from a SQLite database. |
| [Get-SQLiteTableColumnData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetablecolumndata) | &nbsp; | Retrieves data from a specific column in a SQLite database table. |
| [Get-SQLiteTableData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetabledata) | &nbsp; | Retrieves data from a SQLite database table with optional record limiting. |
| [Get-SQLiteTables](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetables) | &nbsp; | Retrieves a list of table names from a SQLite database. |
| [Get-SQLiteTableSchema](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetableschema) | &nbsp; | Retrieves the schema information for a specified SQLite table. |
| [Get-SQLiteTransaction](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetransaction) | &nbsp; | &nbsp; |
| [Get-SQLiteViewColumnData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqliteviewcolumndata) | &nbsp; | Retrieves column data from a SQLite view with optional record limiting. |
| [Get-SQLiteViewData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqliteviewdata) | &nbsp; | Retrieves data from a SQLite database view with optional record limiting. |
| [Get-SQLiteViews](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqliteviews) | &nbsp; | Retrieves a list of views from a SQLite database. |
| [Get-SQLiteViewSchema](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqliteviewschema) | &nbsp; | Retrieves the SQL schema definition for a SQLite view. |
| [Get-SQLServerSchema](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlserverschema) | &nbsp; | Retrieves the complete schema information from a SQL Server database. |
| [Get-SQLServerTableColumnData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlservertablecolumndata) | &nbsp; | Retrieves data from a specific column in a SQL database table. |
| [Get-SQLServerTableData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlservertabledata) | &nbsp; | Retrieves data from a SQL database table with optional record limiting. |
| [Get-SQLServerTables](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlservertables) | &nbsp; | Retrieves a list of table names from a SQL Server database. |
| [Get-SQLServerTableSchema](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlservertableschema) | &nbsp; | Retrieves the schema information for a specified SQL Server table. |
| [Get-SQLServerTransaction](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlservertransaction) | getsqltx, newsqltx | Creates and returns a SQL Server transaction object for batch operations. |
| [Get-SQLServerViewColumnData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlserverviewcolumndata) | &nbsp; | Retrieves column data from a SQL view with optional record limiting. |
| [Get-SQLServerViewData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlserverviewdata) | &nbsp; | Retrieves data from a SQL database view with optional record limiting. |
| [Get-SQLServerViews](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlserverviews) | &nbsp; | Retrieves a list of views from a SQL Server database. |
| [Get-SQLServerViewSchema](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlserverviewschema) | &nbsp; | Retrieves the SQL schema definition for a SQL Server view. |
| [Get-StoreKeys](https://github.com/genXdev/GenXdev.Data/tree/main#get-storekeys) | getkeys | Retrieves all key names for a given key-value store. |
| [Get-ValueByKeyFromStore](https://github.com/genXdev/GenXdev.Data/tree/main#get-valuebykeyfromstore) | getvalue | Retrieves a value from a JSON-based key-value store. |
| [Initialize-KeyValueStores](https://github.com/genXdev/GenXdev.Data/tree/main#initialize-keyvaluestores) | &nbsp; | Initializes KeyValueStore directory structure for local and OneDrive storage. |
| [Invoke-SQLiteQuery](https://github.com/genXdev/GenXdev.Data/tree/main#invoke-sqlitequery) | &nbsp; | &nbsp; |
| [Invoke-SQLiteStudio](https://github.com/genXdev/GenXdev.Data/tree/main#invoke-sqlitestudio) | &nbsp; | Executes SQLite database queries with support for parameters and transactions. |
| [Invoke-SqlServerQuery](https://github.com/genXdev/GenXdev.Data/tree/main#invoke-sqlserverquery) | &nbsp; | &nbsp; |
| [Invoke-SSMS](https://github.com/genXdev/GenXdev.Data/tree/main#invoke-ssms) | sqlservermanagementstudio, ssms | Launches SQL Server Management Studio (SSMS) after ensuring it is installed. |
| [New-SQLiteDatabase](https://github.com/genXdev/GenXdev.Data/tree/main#new-sqlitedatabase) | &nbsp; | &nbsp; |
| [New-SQLServerDatabase](https://github.com/genXdev/GenXdev.Data/tree/main#new-sqlserverdatabase) | nsqldb | Creates a new SQL Server database. |
| [Remove-GenXdevPreference](https://github.com/genXdev/GenXdev.Data/tree/main#remove-genxdevpreference) | removePreference | Removes a preference value from the GenXdev preferences store. |
| [Remove-KeyFromStore](https://github.com/genXdev/GenXdev.Data/tree/main#remove-keyfromstore) | removekey | Removes a key from a key-value store. |
| [Remove-KeyValueStore](https://github.com/genXdev/GenXdev.Data/tree/main#remove-keyvaluestore) | &nbsp; | Removes a key-value store. |
| [Set-GenXdevDefaultPreference](https://github.com/genXdev/GenXdev.Data/tree/main#set-genxdevdefaultpreference) | setPreferenceDefault | Sets a default preference value in the GenXdev preferences store. |
| [Set-GenXdevPreference](https://github.com/genXdev/GenXdev.Data/tree/main#set-genxdevpreference) | setPreference | Sets a preference value in the GenXdev preferences store. |
| [Set-GenXdevPreferencesDatabasePath](https://github.com/genXdev/GenXdev.Data/tree/main#set-genxdevpreferencesdatabasepath) | &nbsp; | Sets the database path for preferences used in GenXdev.Data operations. |
| [Set-ValueByKeyInStore](https://github.com/genXdev/GenXdev.Data/tree/main#set-valuebykeyinstore) | setvalue | Manages key-value pairs in a JSON file-based store. |
| [Sync-KeyValueStore](https://github.com/genXdev/GenXdev.Data/tree/main#sync-keyvaluestore) | &nbsp; | Synchronizes local and OneDrive key-value store JSON files. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Data/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Data.SQLite

**A Windows PowerShell module for enhancing the commandline experience**

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [EnsureSQLiteStudioInstalled](https://github.com/genXdev/GenXdev.Data/tree/main#ensuresqlitestudioinstalled) | &nbsp; | &nbsp; |
| [EnsureSSMSInstalled](https://github.com/genXdev/GenXdev.Data/tree/main#ensuressmsinstalled) | &nbsp; | &nbsp; |
| [Get-GenXdevPreference](https://github.com/genXdev/GenXdev.Data/tree/main#get-genxdevpreference) | getPreference | Retrieves a preference value from the GenXdev preferences store. |
| [Get-GenXdevPreferenceNames](https://github.com/genXdev/GenXdev.Data/tree/main#get-genxdevpreferencenames) | getPreferenceNames | Gets all preference names from session storage and database stores. |
| [Get-GenXdevPreferencesDatabasePath](https://github.com/genXdev/GenXdev.Data/tree/main#get-genxdevpreferencesdatabasepath) | &nbsp; | Gets the configured database path for preference data files used in GenXdev.Data operations. |
| [Get-KeyValueStoreNames](https://github.com/genXdev/GenXdev.Data/tree/main#get-keyvaluestorenames) | getstorenames | Retrieves the names of available key-value stores. |
| [Get-KeyValueStorePath](https://github.com/genXdev/GenXdev.Data/tree/main#get-keyvaluestorepath) | &nbsp; | Gets the file path for a key-value store. |
| [Get-SQLiteSchema](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqliteschema) | &nbsp; | Retrieves the complete schema information from a SQLite database. |
| [Get-SQLiteTableColumnData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetablecolumndata) | &nbsp; | Retrieves data from a specific column in a SQLite database table. |
| [Get-SQLiteTableData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetabledata) | &nbsp; | Retrieves data from a SQLite database table with optional record limiting. |
| [Get-SQLiteTables](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetables) | &nbsp; | Retrieves a list of table names from a SQLite database. |
| [Get-SQLiteTableSchema](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetableschema) | &nbsp; | Retrieves the schema information for a specified SQLite table. |
| [Get-SQLiteTransaction](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetransaction) | &nbsp; | &nbsp; |
| [Get-SQLiteViewColumnData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqliteviewcolumndata) | &nbsp; | Retrieves column data from a SQLite view with optional record limiting. |
| [Get-SQLiteViewData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqliteviewdata) | &nbsp; | Retrieves data from a SQLite database view with optional record limiting. |
| [Get-SQLiteViews](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqliteviews) | &nbsp; | Retrieves a list of views from a SQLite database. |
| [Get-SQLiteViewSchema](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqliteviewschema) | &nbsp; | Retrieves the SQL schema definition for a SQLite view. |
| [Get-SQLServerSchema](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlserverschema) | &nbsp; | Retrieves the complete schema information from a SQL Server database. |
| [Get-SQLServerTableColumnData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlservertablecolumndata) | &nbsp; | Retrieves data from a specific column in a SQL database table. |
| [Get-SQLServerTableData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlservertabledata) | &nbsp; | Retrieves data from a SQL database table with optional record limiting. |
| [Get-SQLServerTables](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlservertables) | &nbsp; | Retrieves a list of table names from a SQL Server database. |
| [Get-SQLServerTableSchema](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlservertableschema) | &nbsp; | Retrieves the schema information for a specified SQL Server table. |
| [Get-SQLServerTransaction](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlservertransaction) | getsqltx, newsqltx | Creates and returns a SQL Server transaction object for batch operations. |
| [Get-SQLServerViewColumnData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlserverviewcolumndata) | &nbsp; | Retrieves column data from a SQL view with optional record limiting. |
| [Get-SQLServerViewData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlserverviewdata) | &nbsp; | Retrieves data from a SQL database view with optional record limiting. |
| [Get-SQLServerViews](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlserverviews) | &nbsp; | Retrieves a list of views from a SQL Server database. |
| [Get-SQLServerViewSchema](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlserverviewschema) | &nbsp; | Retrieves the SQL schema definition for a SQL Server view. |
| [Get-StoreKeys](https://github.com/genXdev/GenXdev.Data/tree/main#get-storekeys) | getkeys | Retrieves all key names for a given key-value store. |
| [Get-ValueByKeyFromStore](https://github.com/genXdev/GenXdev.Data/tree/main#get-valuebykeyfromstore) | getvalue | Retrieves a value from a JSON-based key-value store. |
| [Initialize-KeyValueStores](https://github.com/genXdev/GenXdev.Data/tree/main#initialize-keyvaluestores) | &nbsp; | Initializes KeyValueStore directory structure for local and OneDrive storage. |
| [Invoke-SQLiteQuery](https://github.com/genXdev/GenXdev.Data/tree/main#invoke-sqlitequery) | &nbsp; | &nbsp; |
| [Invoke-SQLiteStudio](https://github.com/genXdev/GenXdev.Data/tree/main#invoke-sqlitestudio) | &nbsp; | Executes SQLite database queries with support for parameters and transactions. |
| [Invoke-SqlServerQuery](https://github.com/genXdev/GenXdev.Data/tree/main#invoke-sqlserverquery) | &nbsp; | &nbsp; |
| [Invoke-SSMS](https://github.com/genXdev/GenXdev.Data/tree/main#invoke-ssms) | sqlservermanagementstudio, ssms | Launches SQL Server Management Studio (SSMS) after ensuring it is installed. |
| [New-SQLiteDatabase](https://github.com/genXdev/GenXdev.Data/tree/main#new-sqlitedatabase) | &nbsp; | &nbsp; |
| [New-SQLServerDatabase](https://github.com/genXdev/GenXdev.Data/tree/main#new-sqlserverdatabase) | nsqldb | Creates a new SQL Server database. |
| [Remove-GenXdevPreference](https://github.com/genXdev/GenXdev.Data/tree/main#remove-genxdevpreference) | removePreference | Removes a preference value from the GenXdev preferences store. |
| [Remove-KeyFromStore](https://github.com/genXdev/GenXdev.Data/tree/main#remove-keyfromstore) | removekey | Removes a key from a key-value store. |
| [Remove-KeyValueStore](https://github.com/genXdev/GenXdev.Data/tree/main#remove-keyvaluestore) | &nbsp; | Removes a key-value store. |
| [Set-GenXdevDefaultPreference](https://github.com/genXdev/GenXdev.Data/tree/main#set-genxdevdefaultpreference) | setPreferenceDefault | Sets a default preference value in the GenXdev preferences store. |
| [Set-GenXdevPreference](https://github.com/genXdev/GenXdev.Data/tree/main#set-genxdevpreference) | setPreference | Sets a preference value in the GenXdev preferences store. |
| [Set-GenXdevPreferencesDatabasePath](https://github.com/genXdev/GenXdev.Data/tree/main#set-genxdevpreferencesdatabasepath) | &nbsp; | Sets the database path for preferences used in GenXdev.Data operations. |
| [Set-ValueByKeyInStore](https://github.com/genXdev/GenXdev.Data/tree/main#set-valuebykeyinstore) | setvalue | Manages key-value pairs in a JSON file-based store. |
| [Sync-KeyValueStore](https://github.com/genXdev/GenXdev.Data/tree/main#sync-keyvaluestore) | &nbsp; | Synchronizes local and OneDrive key-value store JSON files. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Data/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Data.SqlServer

**A Windows PowerShell module for enhancing the commandline experience**

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [EnsureSQLiteStudioInstalled](https://github.com/genXdev/GenXdev.Data/tree/main#ensuresqlitestudioinstalled) | &nbsp; | &nbsp; |
| [EnsureSSMSInstalled](https://github.com/genXdev/GenXdev.Data/tree/main#ensuressmsinstalled) | &nbsp; | &nbsp; |
| [Get-GenXdevPreference](https://github.com/genXdev/GenXdev.Data/tree/main#get-genxdevpreference) | getPreference | Retrieves a preference value from the GenXdev preferences store. |
| [Get-GenXdevPreferenceNames](https://github.com/genXdev/GenXdev.Data/tree/main#get-genxdevpreferencenames) | getPreferenceNames | Gets all preference names from session storage and database stores. |
| [Get-GenXdevPreferencesDatabasePath](https://github.com/genXdev/GenXdev.Data/tree/main#get-genxdevpreferencesdatabasepath) | &nbsp; | Gets the configured database path for preference data files used in GenXdev.Data operations. |
| [Get-KeyValueStoreNames](https://github.com/genXdev/GenXdev.Data/tree/main#get-keyvaluestorenames) | getstorenames | Retrieves the names of available key-value stores. |
| [Get-KeyValueStorePath](https://github.com/genXdev/GenXdev.Data/tree/main#get-keyvaluestorepath) | &nbsp; | Gets the file path for a key-value store. |
| [Get-SQLiteSchema](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqliteschema) | &nbsp; | Retrieves the complete schema information from a SQLite database. |
| [Get-SQLiteTableColumnData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetablecolumndata) | &nbsp; | Retrieves data from a specific column in a SQLite database table. |
| [Get-SQLiteTableData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetabledata) | &nbsp; | Retrieves data from a SQLite database table with optional record limiting. |
| [Get-SQLiteTables](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetables) | &nbsp; | Retrieves a list of table names from a SQLite database. |
| [Get-SQLiteTableSchema](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetableschema) | &nbsp; | Retrieves the schema information for a specified SQLite table. |
| [Get-SQLiteTransaction](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetransaction) | &nbsp; | &nbsp; |
| [Get-SQLiteViewColumnData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqliteviewcolumndata) | &nbsp; | Retrieves column data from a SQLite view with optional record limiting. |
| [Get-SQLiteViewData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqliteviewdata) | &nbsp; | Retrieves data from a SQLite database view with optional record limiting. |
| [Get-SQLiteViews](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqliteviews) | &nbsp; | Retrieves a list of views from a SQLite database. |
| [Get-SQLiteViewSchema](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqliteviewschema) | &nbsp; | Retrieves the SQL schema definition for a SQLite view. |
| [Get-SQLServerSchema](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlserverschema) | &nbsp; | Retrieves the complete schema information from a SQL Server database. |
| [Get-SQLServerTableColumnData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlservertablecolumndata) | &nbsp; | Retrieves data from a specific column in a SQL database table. |
| [Get-SQLServerTableData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlservertabledata) | &nbsp; | Retrieves data from a SQL database table with optional record limiting. |
| [Get-SQLServerTables](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlservertables) | &nbsp; | Retrieves a list of table names from a SQL Server database. |
| [Get-SQLServerTableSchema](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlservertableschema) | &nbsp; | Retrieves the schema information for a specified SQL Server table. |
| [Get-SQLServerTransaction](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlservertransaction) | getsqltx, newsqltx | Creates and returns a SQL Server transaction object for batch operations. |
| [Get-SQLServerViewColumnData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlserverviewcolumndata) | &nbsp; | Retrieves column data from a SQL view with optional record limiting. |
| [Get-SQLServerViewData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlserverviewdata) | &nbsp; | Retrieves data from a SQL database view with optional record limiting. |
| [Get-SQLServerViews](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlserverviews) | &nbsp; | Retrieves a list of views from a SQL Server database. |
| [Get-SQLServerViewSchema](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlserverviewschema) | &nbsp; | Retrieves the SQL schema definition for a SQL Server view. |
| [Get-StoreKeys](https://github.com/genXdev/GenXdev.Data/tree/main#get-storekeys) | getkeys | Retrieves all key names for a given key-value store. |
| [Get-ValueByKeyFromStore](https://github.com/genXdev/GenXdev.Data/tree/main#get-valuebykeyfromstore) | getvalue | Retrieves a value from a JSON-based key-value store. |
| [Initialize-KeyValueStores](https://github.com/genXdev/GenXdev.Data/tree/main#initialize-keyvaluestores) | &nbsp; | Initializes KeyValueStore directory structure for local and OneDrive storage. |
| [Invoke-SQLiteQuery](https://github.com/genXdev/GenXdev.Data/tree/main#invoke-sqlitequery) | &nbsp; | &nbsp; |
| [Invoke-SQLiteStudio](https://github.com/genXdev/GenXdev.Data/tree/main#invoke-sqlitestudio) | &nbsp; | Executes SQLite database queries with support for parameters and transactions. |
| [Invoke-SqlServerQuery](https://github.com/genXdev/GenXdev.Data/tree/main#invoke-sqlserverquery) | &nbsp; | &nbsp; |
| [Invoke-SSMS](https://github.com/genXdev/GenXdev.Data/tree/main#invoke-ssms) | sqlservermanagementstudio, ssms | Launches SQL Server Management Studio (SSMS) after ensuring it is installed. |
| [New-SQLiteDatabase](https://github.com/genXdev/GenXdev.Data/tree/main#new-sqlitedatabase) | &nbsp; | &nbsp; |
| [New-SQLServerDatabase](https://github.com/genXdev/GenXdev.Data/tree/main#new-sqlserverdatabase) | nsqldb | Creates a new SQL Server database. |
| [Remove-GenXdevPreference](https://github.com/genXdev/GenXdev.Data/tree/main#remove-genxdevpreference) | removePreference | Removes a preference value from the GenXdev preferences store. |
| [Remove-KeyFromStore](https://github.com/genXdev/GenXdev.Data/tree/main#remove-keyfromstore) | removekey | Removes a key from a key-value store. |
| [Remove-KeyValueStore](https://github.com/genXdev/GenXdev.Data/tree/main#remove-keyvaluestore) | &nbsp; | Removes a key-value store. |
| [Set-GenXdevDefaultPreference](https://github.com/genXdev/GenXdev.Data/tree/main#set-genxdevdefaultpreference) | setPreferenceDefault | Sets a default preference value in the GenXdev preferences store. |
| [Set-GenXdevPreference](https://github.com/genXdev/GenXdev.Data/tree/main#set-genxdevpreference) | setPreference | Sets a preference value in the GenXdev preferences store. |
| [Set-GenXdevPreferencesDatabasePath](https://github.com/genXdev/GenXdev.Data/tree/main#set-genxdevpreferencesdatabasepath) | &nbsp; | Sets the database path for preferences used in GenXdev.Data operations. |
| [Set-ValueByKeyInStore](https://github.com/genXdev/GenXdev.Data/tree/main#set-valuebykeyinstore) | setvalue | Manages key-value pairs in a JSON file-based store. |
| [Sync-KeyValueStore](https://github.com/genXdev/GenXdev.Data/tree/main#sync-keyvaluestore) | &nbsp; | Synchronizes local and OneDrive key-value store JSON files. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Data/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.FileSystem

**A Windows PowerShell module for basic and advanced file management tasks**

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [Confirm-InstallationConsent](https://github.com/genXdev/GenXdev.FileSystem/tree/main#confirm-installationconsent) | &nbsp; | &nbsp; |
| [Copy-IdenticalParamValues](https://github.com/genXdev/GenXdev.FileSystem/tree/main#copy-identicalparamvalues) | &nbsp; | &nbsp; |
| [EnsurePester](https://github.com/genXdev/GenXdev.FileSystem/tree/main#ensurepester) | &nbsp; | &nbsp; |
| [Expand-Path](https://github.com/genXdev/GenXdev.FileSystem/tree/main#expand-path) | ep | Expands any given file reference to a full pathname. |
| [Find-DuplicateFiles](https://github.com/genXdev/GenXdev.FileSystem/tree/main#find-duplicatefiles) | fdf | Find duplicate files across multiple directories based on configurable criteria. |
| [Find-Item](https://github.com/genXdev/GenXdev.FileSystem/tree/main#find-item) | l | Fast multi-threaded file and directory search with optional textcontent pattern matching capabilities. |
| [Invoke-Fasti](https://github.com/genXdev/GenXdev.FileSystem/tree/main#invoke-fasti) | fasti | &nbsp; |
| [Move-ItemWithTracking](https://github.com/genXdev/GenXdev.FileSystem/tree/main#move-itemwithtracking) | &nbsp; | Moves files and directories while preserving filesystem links and references. |
| [Move-ToRecycleBin](https://github.com/genXdev/GenXdev.FileSystem/tree/main#move-torecyclebin) | &nbsp; | Moves files and directories to the Windows Recycle Bin safely. |
| [ReadJsonWithRetry](https://github.com/genXdev/GenXdev.FileSystem/tree/main#readjsonwithretry) | &nbsp; | Reads JSON file with retry logic and automatic lock cleanup. |
| [Remove-AllItems](https://github.com/genXdev/GenXdev.FileSystem/tree/main#remove-allitems) | sdel | &nbsp; |
| [Remove-ItemWithFallback](https://github.com/genXdev/GenXdev.FileSystem/tree/main#remove-itemwithfallback) | rmf | &nbsp; |
| [Remove-OnReboot](https://github.com/genXdev/GenXdev.FileSystem/tree/main#remove-onreboot) | &nbsp; | Marks files or directories for deletion during the next system boot. |
| [Rename-InProject](https://github.com/genXdev/GenXdev.FileSystem/tree/main#rename-inproject) | rip | &nbsp; |
| [ResolveInputObjectFileNames](https://github.com/genXdev/GenXdev.FileSystem/tree/main#resolveinputobjectfilenames) | &nbsp; | &nbsp; |
| [Set-FoundLocation](https://github.com/genXdev/GenXdev.FileSystem/tree/main#set-foundlocation) | lcd | Finds the first matching file or folder and sets the location to it. |
| [Set-LocationParent](https://github.com/genXdev/GenXdev.FileSystem/tree/main#set-locationparent) | .. | Changes the current location to the parent directory and lists its contents. |
| [Set-LocationParent2](https://github.com/genXdev/GenXdev.FileSystem/tree/main#set-locationparent2) | ... | Navigates up two directory levels in the file system hierarchy. |
| [Set-LocationParent3](https://github.com/genXdev/GenXdev.FileSystem/tree/main#set-locationparent3) | .... | Navigates up three directory levels in the file system hierarchy. |
| [Set-LocationParent4](https://github.com/genXdev/GenXdev.FileSystem/tree/main#set-locationparent4) | ..... | Navigates up four directory levels in the filesystem hierarchy. |
| [Set-LocationParent5](https://github.com/genXdev/GenXdev.FileSystem/tree/main#set-locationparent5) | ...... | Navigates up five directory levels in the file system hierarchy. |
| [Start-RoboCopy](https://github.com/genXdev/GenXdev.FileSystem/tree/main#start-robocopy) | rc, xc | &nbsp; |
| [WriteFileOutput](https://github.com/genXdev/GenXdev.FileSystem/tree/main#writefileoutput) | &nbsp; | &nbsp; |
| [WriteJsonAtomic](https://github.com/genXdev/GenXdev.FileSystem/tree/main#writejsonatomic) | &nbsp; | &nbsp; |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.FileSystem/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Helpers

**A Windows PowerShell module with helpers mostly used by other GenXdev modules**

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [alignScript](https://github.com/genXdev/GenXdev.Helpers/tree/main#alignscript) | &nbsp; | Returns a string (with altered indentation) of a provided scriptblock string |
| [Convert-PhysicsUnit](https://github.com/genXdev/GenXdev.Helpers/tree/main#convert-physicsunit) | &nbsp; | Converts a value from one physics unit to another within the same category. |
| [ConvertTo-HashTable](https://github.com/genXdev/GenXdev.Helpers/tree/main#convertto-hashtable) | &nbsp; | Converts a PSCustomObject to a HashTable recursively. |
| [EnsureGenXdev](https://github.com/genXdev/GenXdev.Helpers/tree/main#ensuregenxdev) | &nbsp; | &nbsp; |
| [EnsureNuGetAssembly](https://github.com/genXdev/GenXdev.Helpers/tree/main#ensurenugetassembly) | &nbsp; | Downloads and loads .NET assemblies from NuGet packages based on package key or ID. |
| [Get-ApparentSizeAtArmLength](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-apparentsizeatarmlength) | &nbsp; | Calculates the apparent size of an object at arm's length. |
| [Get-AtEyeLengthSizeInMM](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-ateyelengthsizeinmm) | &nbsp; | Calculates the apparent size in mm of an object at arm's length, based on its actual size and distance. |
| [Get-BuoyantForceByDisplacedVolumeAndDensity](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-buoyantforcebydisplacedvolumeanddensity) | &nbsp; | Calculates buoyant force. |
| [Get-CentripetalAccelerationByVelocityAndRadius](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-centripetalaccelerationbyvelocityandradius) | &nbsp; | Calculates centripetal acceleration. |
| [Get-DefaultWebLanguage](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-defaultweblanguage) | &nbsp; | Gets the default web language key based on the system's current language settings. |
| [Get-DopplerFrequencyShiftBySourceSpeedAndObserverSpeed](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-dopplerfrequencyshiftbysourcespeedandobserverspeed) | &nbsp; | Calculates Doppler shifted frequency. |
| [Get-DragForceByVelocityDensityAreaAndCoefficient](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-dragforcebyvelocitydensityareaandcoefficient) | &nbsp; | Calculates drag force. |
| [Get-EscapeVelocityByMassAndRadius](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-escapevelocitybymassandradius) | &nbsp; | Calculates escape velocity. |
| [Get-FreeFallDistance](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-freefalldistance) | &nbsp; | Calculates the distance fallen during free fall for a given time duration. |
| [Get-FreeFallHeight](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-freefallheight) | &nbsp; | Calculates the height fallen during free fall for a given time duration. |
| [Get-FreeFallTime](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-freefalltime) | &nbsp; | Calculates the time required for an object to fall a given height during free fall. |
| [Get-GenXDevCmdlet](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-genxdevcmdlet) | gcmds | Retrieves and lists all GenXdev cmdlets and their details. |
| [Get-ImageGeolocation](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-imagegeolocation) | &nbsp; | Extracts geolocation data from an image file. |
| [Get-ImageMetadata](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-imagemetadata) | &nbsp; | &nbsp; |
| [Get-ImpactVelocityByHeightAndGravity](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-impactvelocitybyheightandgravity) | &nbsp; | Calculates impact velocity from height. |
| [Get-KineticEnergyByMassAndVelocity](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-kineticenergybymassandvelocity) | &nbsp; | Calculates kinetic energy. |
| [Get-LightTravelTimeByDistance](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-lighttraveltimebydistance) | &nbsp; | Calculates time for light to travel a distance. |
| [Get-MagnificationByObjectDistanceAndImageDistance](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-magnificationbyobjectdistanceandimagedistance) | &nbsp; | Calculates magnification for a lens. |
| [Get-MomentumByMassAndVelocity](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-momentumbymassandvelocity) | &nbsp; | Calculates linear momentum. |
| [Get-OrbitalVelocityByRadiusAndMass](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-orbitalvelocitybyradiusandmass) | &nbsp; | Calculates orbital velocity. |
| [Get-PotentialEnergyByMassHeightAndGravity](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-potentialenergybymassheightandgravity) | &nbsp; | Calculates gravitational potential energy. |
| [Get-ProjectileRangeByInitialSpeedAndAngle](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-projectilerangebyinitialspeedandangle) | &nbsp; | Calculates the range of a projectile. |
| [Get-RefractionAngleByIncidentAngleAndIndices](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-refractionanglebyincidentangleandindices) | &nbsp; | Calculates refraction angle using Snell's law. |
| [Get-ResonantFrequencyByLengthAndSpeed](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-resonantfrequencybylengthandspeed) | &nbsp; | Calculates resonant frequency for a closed pipe. |
| [Get-SoundTravelDistanceByTime](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-soundtraveldistancebytime) | &nbsp; | Calculates the distance sound travels in a given time. |
| [Get-TerminalVelocityByMassGravityDensityAndArea](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-terminalvelocitybymassgravitydensityandarea) | &nbsp; | Calculates terminal velocity. |
| [Get-TimeOfFlightByInitialVelocityAndAngle](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-timeofflightbyinitialvelocityandangle) | &nbsp; | Calculates the time of flight for a projectile. |
| [Get-WaveSpeedByFrequencyAndWavelength](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-wavespeedbyfrequencyandwavelength) | &nbsp; | Calculates wave speed. |
| [Get-WebLanguageDictionary](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-weblanguagedictionary) | &nbsp; | Returns a reversed dictionary for all languages supported by Google Search |
| [GetSpeechToText](https://github.com/genXdev/GenXdev.Helpers/tree/main#getspeechtotext) | &nbsp; | Converts audio files to text using OpenAI's Whisper speech recognition model. |
| [Import-GenXdevModules](https://github.com/genXdev/GenXdev.Helpers/tree/main#import-genxdevmodules) | reloadgenxdev | Imports all GenXdev PowerShell modules into the global scope. |
| [Initialize-SearchPaths](https://github.com/genXdev/GenXdev.Helpers/tree/main#initialize-searchpaths) | &nbsp; | Initializes and configures system search paths for package management. |
| [Invoke-OnEachGenXdevModule](https://github.com/genXdev/GenXdev.Helpers/tree/main#invoke-oneachgenxdevmodule) | foreach-genxdev-module-do | Executes a script block on each GenXdev module in the workspace. |
| [Out-Serial](https://github.com/genXdev/GenXdev.Helpers/tree/main#out-serial) | &nbsp; | Sends a string to a serial port |
| [ReceiveRealTimeSpeechToText](https://github.com/genXdev/GenXdev.Helpers/tree/main#receiverealtimespeechtotext) | &nbsp; | &nbsp; |
| [resetdefaultmonitor](https://github.com/genXdev/GenXdev.Helpers/tree/main#resetdefaultmonitor) | &nbsp; | &nbsp; |
| [SecondScreen](https://github.com/genXdev/GenXdev.Helpers/tree/main#secondscreen) | &nbsp; | Sets default second-monitor configuration. |
| [Show-GenXDevCmdlet](https://github.com/genXdev/GenXdev.Helpers/tree/main#show-genxdevcmdlet) | cmds | Displays GenXdev PowerShell modules with their cmdlets and aliases. |
| [Show-Verb](https://github.com/genXdev/GenXdev.Helpers/tree/main#show-verb) | showverbs | Shows a short alphabetical list of all PowerShell verbs. |
| [SideBySide](https://github.com/genXdev/GenXdev.Helpers/tree/main#sidebyside) | &nbsp; | Sets default side-by-side configuration. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Helpers.Physics

**A Windows PowerShell module with helpers mostly used by other GenXdev modules**

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [alignScript](https://github.com/genXdev/GenXdev.Helpers/tree/main#alignscript) | &nbsp; | Returns a string (with altered indentation) of a provided scriptblock string |
| [Convert-PhysicsUnit](https://github.com/genXdev/GenXdev.Helpers/tree/main#convert-physicsunit) | &nbsp; | Converts a value from one physics unit to another within the same category. |
| [ConvertTo-HashTable](https://github.com/genXdev/GenXdev.Helpers/tree/main#convertto-hashtable) | &nbsp; | Converts a PSCustomObject to a HashTable recursively. |
| [EnsureGenXdev](https://github.com/genXdev/GenXdev.Helpers/tree/main#ensuregenxdev) | &nbsp; | &nbsp; |
| [EnsureNuGetAssembly](https://github.com/genXdev/GenXdev.Helpers/tree/main#ensurenugetassembly) | &nbsp; | Downloads and loads .NET assemblies from NuGet packages based on package key or ID. |
| [Get-ApparentSizeAtArmLength](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-apparentsizeatarmlength) | &nbsp; | Calculates the apparent size of an object at arm's length. |
| [Get-AtEyeLengthSizeInMM](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-ateyelengthsizeinmm) | &nbsp; | Calculates the apparent size in mm of an object at arm's length, based on its actual size and distance. |
| [Get-BuoyantForceByDisplacedVolumeAndDensity](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-buoyantforcebydisplacedvolumeanddensity) | &nbsp; | Calculates buoyant force. |
| [Get-CentripetalAccelerationByVelocityAndRadius](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-centripetalaccelerationbyvelocityandradius) | &nbsp; | Calculates centripetal acceleration. |
| [Get-DefaultWebLanguage](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-defaultweblanguage) | &nbsp; | Gets the default web language key based on the system's current language settings. |
| [Get-DopplerFrequencyShiftBySourceSpeedAndObserverSpeed](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-dopplerfrequencyshiftbysourcespeedandobserverspeed) | &nbsp; | Calculates Doppler shifted frequency. |
| [Get-DragForceByVelocityDensityAreaAndCoefficient](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-dragforcebyvelocitydensityareaandcoefficient) | &nbsp; | Calculates drag force. |
| [Get-EscapeVelocityByMassAndRadius](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-escapevelocitybymassandradius) | &nbsp; | Calculates escape velocity. |
| [Get-FreeFallDistance](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-freefalldistance) | &nbsp; | Calculates the distance fallen during free fall for a given time duration. |
| [Get-FreeFallHeight](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-freefallheight) | &nbsp; | Calculates the height fallen during free fall for a given time duration. |
| [Get-FreeFallTime](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-freefalltime) | &nbsp; | Calculates the time required for an object to fall a given height during free fall. |
| [Get-GenXDevCmdlet](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-genxdevcmdlet) | gcmds | Retrieves and lists all GenXdev cmdlets and their details. |
| [Get-ImageGeolocation](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-imagegeolocation) | &nbsp; | Extracts geolocation data from an image file. |
| [Get-ImageMetadata](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-imagemetadata) | &nbsp; | &nbsp; |
| [Get-ImpactVelocityByHeightAndGravity](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-impactvelocitybyheightandgravity) | &nbsp; | Calculates impact velocity from height. |
| [Get-KineticEnergyByMassAndVelocity](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-kineticenergybymassandvelocity) | &nbsp; | Calculates kinetic energy. |
| [Get-LightTravelTimeByDistance](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-lighttraveltimebydistance) | &nbsp; | Calculates time for light to travel a distance. |
| [Get-MagnificationByObjectDistanceAndImageDistance](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-magnificationbyobjectdistanceandimagedistance) | &nbsp; | Calculates magnification for a lens. |
| [Get-MomentumByMassAndVelocity](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-momentumbymassandvelocity) | &nbsp; | Calculates linear momentum. |
| [Get-OrbitalVelocityByRadiusAndMass](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-orbitalvelocitybyradiusandmass) | &nbsp; | Calculates orbital velocity. |
| [Get-PotentialEnergyByMassHeightAndGravity](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-potentialenergybymassheightandgravity) | &nbsp; | Calculates gravitational potential energy. |
| [Get-ProjectileRangeByInitialSpeedAndAngle](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-projectilerangebyinitialspeedandangle) | &nbsp; | Calculates the range of a projectile. |
| [Get-RefractionAngleByIncidentAngleAndIndices](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-refractionanglebyincidentangleandindices) | &nbsp; | Calculates refraction angle using Snell's law. |
| [Get-ResonantFrequencyByLengthAndSpeed](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-resonantfrequencybylengthandspeed) | &nbsp; | Calculates resonant frequency for a closed pipe. |
| [Get-SoundTravelDistanceByTime](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-soundtraveldistancebytime) | &nbsp; | Calculates the distance sound travels in a given time. |
| [Get-TerminalVelocityByMassGravityDensityAndArea](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-terminalvelocitybymassgravitydensityandarea) | &nbsp; | Calculates terminal velocity. |
| [Get-TimeOfFlightByInitialVelocityAndAngle](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-timeofflightbyinitialvelocityandangle) | &nbsp; | Calculates the time of flight for a projectile. |
| [Get-WaveSpeedByFrequencyAndWavelength](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-wavespeedbyfrequencyandwavelength) | &nbsp; | Calculates wave speed. |
| [Get-WebLanguageDictionary](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-weblanguagedictionary) | &nbsp; | Returns a reversed dictionary for all languages supported by Google Search |
| [GetSpeechToText](https://github.com/genXdev/GenXdev.Helpers/tree/main#getspeechtotext) | &nbsp; | Converts audio files to text using OpenAI's Whisper speech recognition model. |
| [Import-GenXdevModules](https://github.com/genXdev/GenXdev.Helpers/tree/main#import-genxdevmodules) | reloadgenxdev | Imports all GenXdev PowerShell modules into the global scope. |
| [Initialize-SearchPaths](https://github.com/genXdev/GenXdev.Helpers/tree/main#initialize-searchpaths) | &nbsp; | Initializes and configures system search paths for package management. |
| [Invoke-OnEachGenXdevModule](https://github.com/genXdev/GenXdev.Helpers/tree/main#invoke-oneachgenxdevmodule) | foreach-genxdev-module-do | Executes a script block on each GenXdev module in the workspace. |
| [Out-Serial](https://github.com/genXdev/GenXdev.Helpers/tree/main#out-serial) | &nbsp; | Sends a string to a serial port |
| [ReceiveRealTimeSpeechToText](https://github.com/genXdev/GenXdev.Helpers/tree/main#receiverealtimespeechtotext) | &nbsp; | &nbsp; |
| [resetdefaultmonitor](https://github.com/genXdev/GenXdev.Helpers/tree/main#resetdefaultmonitor) | &nbsp; | &nbsp; |
| [SecondScreen](https://github.com/genXdev/GenXdev.Helpers/tree/main#secondscreen) | &nbsp; | Sets default second-monitor configuration. |
| [Show-GenXDevCmdlet](https://github.com/genXdev/GenXdev.Helpers/tree/main#show-genxdevcmdlet) | cmds | Displays GenXdev PowerShell modules with their cmdlets and aliases. |
| [Show-Verb](https://github.com/genXdev/GenXdev.Helpers/tree/main#show-verb) | showverbs | Shows a short alphabetical list of all PowerShell verbs. |
| [SideBySide](https://github.com/genXdev/GenXdev.Helpers/tree/main#sidebyside) | &nbsp; | Sets default side-by-side configuration. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Media

**A Windows PowerShell module that helps with converting media files like pictures and video files**

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [EnsureYtdlp](https://github.com/genXdev/GenXdev.Media/tree/main#ensureytdlp) | &nbsp; | Ensures yt-dlp is installed and available in the default WSL image. |
| [Invoke-YTDlpSaveVideo](https://github.com/genXdev/GenXdev.Media/tree/main#invoke-ytdlpsavevideo) | savevideo | &nbsp; |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Media/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Media.ffmpeg

**A Windows PowerShell module that helps with converting media files like pictures and video files**

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [EnsureYtdlp](https://github.com/genXdev/GenXdev.Media/tree/main#ensureytdlp) | &nbsp; | Ensures yt-dlp is installed and available in the default WSL image. |
| [Invoke-YTDlpSaveVideo](https://github.com/genXdev/GenXdev.Media/tree/main#invoke-ytdlpsavevideo) | savevideo | &nbsp; |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Media/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Media.ytdlp

**A Windows PowerShell module that helps with converting media files like pictures and video files**

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [EnsureYtdlp](https://github.com/genXdev/GenXdev.Media/tree/main#ensureytdlp) | &nbsp; | Ensures yt-dlp is installed and available in the default WSL image. |
| [Invoke-YTDlpSaveVideo](https://github.com/genXdev/GenXdev.Media/tree/main#invoke-ytdlpsavevideo) | savevideo | &nbsp; |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Media/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Queries

**A Windows PowerShell module for finding resources and information on the internet**

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [Clear-YoutubeWatched](https://github.com/genXdev/GenXdev.Queries/tree/main#clear-youtubewatched) | &nbsp; | Clears the YouTube watch history from the browser's local storage. |
| [ConvertTo-Uris](https://github.com/genXdev/GenXdev.Queries/tree/main#convertto-uris) | &nbsp; | Parses strings for any valid URI. |
| [Copy-PDFsFromGoogleQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#copy-pdfsfromgooglequery) | &nbsp; | Downloads PDF files found through Google search results. |
| [Get-GoogleSearchResultUrls](https://github.com/genXdev/GenXdev.Queries/tree/main#get-googlesearchresulturls) | qlinksget | Performs a google search and returns the links |
| [Get-NextAffirmation](https://github.com/genXdev/GenXdev.Queries/tree/main#get-nextaffirmation) | WhatAboutIt | Returns a random affirmation text from affirmations.dev API. |
| [Get-WikipediaSummary](https://github.com/genXdev/GenXdev.Queries/tree/main#get-wikipediasummary) | wikitxt | Retrieves a summary of a topic from Wikipedia. |
| [Invoke-WebbrowserTabPollingScript](https://github.com/genXdev/GenXdev.Queries/tree/main#invoke-webbrowsertabpollingscript) | &nbsp; | &nbsp; |
| [Open-AllGoogleLinks](https://github.com/genXdev/GenXdev.Queries/tree/main#open-allgooglelinks) | qlinks | Performs an infinite auto opening google search. |
| [Open-AllPossibleQueries](https://github.com/genXdev/GenXdev.Queries/tree/main#open-allpossiblequeries) | qq | &nbsp; |
| [Open-AllYoutubeVideos](https://github.com/genXdev/GenXdev.Queries/tree/main#open-allyoutubevideos) | qvideos, qyt | Opens and controls YouTube videos in a browser window with keyboard shortcuts. |
| [Open-BingCopilotQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-bingcopilotquery) | aibc | &nbsp; |
| [Open-BingQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-bingquery) | bq | Opens a Bing search query in a web browser. |
| [Open-BuiltWithSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-builtwithsiteinfo) | &nbsp; | Opens BuiltWith website queries in a web browser. |
| [Open-ChatGPTQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-chatgptquery) | aicgpt, askchatgpt | &nbsp; |
| [Open-CloudLLMChat](https://github.com/genXdev/GenXdev.Queries/tree/main#open-cloudllmchat) | ask | Opens a cloud LLM chat interface for AI queries. |
| [Open-DeepSearchQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-deepsearchquery) | aideepseek, askdeepsearch | &nbsp; |
| [Open-GameOfLife](https://github.com/genXdev/GenXdev.Queries/tree/main#open-gameoflife) | conway, gameoflife | &nbsp; |
| [Open-GenXdevAppCatalog](https://github.com/genXdev/GenXdev.Queries/tree/main#open-genxdevappcatalog) | appcatalog | Opens the GenXdev progressive webapps catalog in a web browser. |
| [Open-GithubCopilotQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-githubcopilotquery) | aigc, askghcopilot | &nbsp; |
| [Open-GithubQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-githubquery) | qgh, qgithub | &nbsp; |
| [Open-GoogleGeminiQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-googlegeminiquery) | aigg, askgemini | &nbsp; |
| [Open-GoogleQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-googlequery) | &nbsp; | &nbsp; |
| [Open-GoogleSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-googlesiteinfo) | &nbsp; | Opens Google site information queries in a web browser. |
| [Open-IMDBQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-imdbquery) | imdb | Opens an IMDB search query in a web browser. |
| [Open-InstantStreetViewQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-instantstreetviewquery) | isv | &nbsp; |
| [Open-MovieQuote](https://github.com/genXdev/GenXdev.Queries/tree/main#open-moviequote) | moviequote | &nbsp; |
| [Open-SearchEngine](https://github.com/genXdev/GenXdev.Queries/tree/main#open-searchengine) | q | Opens a search query in the specified search engine using a web browser. |
| [Open-SimularWebSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-simularwebsiteinfo) | simularsite | &nbsp; |
| [Open-StackOverflowQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-stackoverflowquery) | qso | &nbsp; |
| [Open-Timeline](https://github.com/genXdev/GenXdev.Queries/tree/main#open-timeline) | timeline | &nbsp; |
| [Open-ViralSimulation](https://github.com/genXdev/GenXdev.Queries/tree/main#open-viralsimulation) | viral | &nbsp; |
| [Open-WaybackMachineSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-waybackmachinesiteinfo) | wayback | Opens WaybackMachine site information in a web browser. |
| [Open-WebsiteAndPerformQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-websiteandperformquery) | owaq | &nbsp; |
| [Open-WhoisHostSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-whoishostsiteinfo) | whois | &nbsp; |
| [Open-WikipediaNLQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-wikipedianlquery) | wikinl | &nbsp; |
| [Open-WikipediaQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-wikipediaquery) | wiki | &nbsp; |
| [Open-WolframAlphaQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-wolframalphaquery) | qalpha | &nbsp; |
| [Open-XGrokQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-xgrokquery) | aixg, askxgrok | &nbsp; |
| [Open-Yab](https://github.com/genXdev/GenXdev.Queries/tree/main#open-yab) | yab | Opens the YAB game in a web browser with configurable settings. |
| [Open-YabAIBattle](https://github.com/genXdev/GenXdev.Queries/tree/main#open-yabaibattle) | yabbattle | &nbsp; |
| [Open-YoutubeQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-youtubequery) | youtube | Opens YouTube search queries in a web browser. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Queries.AI

**A Windows PowerShell module for finding resources and information on the internet**

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [Clear-YoutubeWatched](https://github.com/genXdev/GenXdev.Queries/tree/main#clear-youtubewatched) | &nbsp; | Clears the YouTube watch history from the browser's local storage. |
| [ConvertTo-Uris](https://github.com/genXdev/GenXdev.Queries/tree/main#convertto-uris) | &nbsp; | Parses strings for any valid URI. |
| [Copy-PDFsFromGoogleQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#copy-pdfsfromgooglequery) | &nbsp; | Downloads PDF files found through Google search results. |
| [Get-GoogleSearchResultUrls](https://github.com/genXdev/GenXdev.Queries/tree/main#get-googlesearchresulturls) | qlinksget | Performs a google search and returns the links |
| [Get-NextAffirmation](https://github.com/genXdev/GenXdev.Queries/tree/main#get-nextaffirmation) | WhatAboutIt | Returns a random affirmation text from affirmations.dev API. |
| [Get-WikipediaSummary](https://github.com/genXdev/GenXdev.Queries/tree/main#get-wikipediasummary) | wikitxt | Retrieves a summary of a topic from Wikipedia. |
| [Invoke-WebbrowserTabPollingScript](https://github.com/genXdev/GenXdev.Queries/tree/main#invoke-webbrowsertabpollingscript) | &nbsp; | &nbsp; |
| [Open-AllGoogleLinks](https://github.com/genXdev/GenXdev.Queries/tree/main#open-allgooglelinks) | qlinks | Performs an infinite auto opening google search. |
| [Open-AllPossibleQueries](https://github.com/genXdev/GenXdev.Queries/tree/main#open-allpossiblequeries) | qq | &nbsp; |
| [Open-AllYoutubeVideos](https://github.com/genXdev/GenXdev.Queries/tree/main#open-allyoutubevideos) | qvideos, qyt | Opens and controls YouTube videos in a browser window with keyboard shortcuts. |
| [Open-BingCopilotQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-bingcopilotquery) | aibc | &nbsp; |
| [Open-BingQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-bingquery) | bq | Opens a Bing search query in a web browser. |
| [Open-BuiltWithSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-builtwithsiteinfo) | &nbsp; | Opens BuiltWith website queries in a web browser. |
| [Open-ChatGPTQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-chatgptquery) | aicgpt, askchatgpt | &nbsp; |
| [Open-CloudLLMChat](https://github.com/genXdev/GenXdev.Queries/tree/main#open-cloudllmchat) | ask | Opens a cloud LLM chat interface for AI queries. |
| [Open-DeepSearchQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-deepsearchquery) | aideepseek, askdeepsearch | &nbsp; |
| [Open-GameOfLife](https://github.com/genXdev/GenXdev.Queries/tree/main#open-gameoflife) | conway, gameoflife | &nbsp; |
| [Open-GenXdevAppCatalog](https://github.com/genXdev/GenXdev.Queries/tree/main#open-genxdevappcatalog) | appcatalog | Opens the GenXdev progressive webapps catalog in a web browser. |
| [Open-GithubCopilotQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-githubcopilotquery) | aigc, askghcopilot | &nbsp; |
| [Open-GithubQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-githubquery) | qgh, qgithub | &nbsp; |
| [Open-GoogleGeminiQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-googlegeminiquery) | aigg, askgemini | &nbsp; |
| [Open-GoogleQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-googlequery) | &nbsp; | &nbsp; |
| [Open-GoogleSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-googlesiteinfo) | &nbsp; | Opens Google site information queries in a web browser. |
| [Open-IMDBQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-imdbquery) | imdb | Opens an IMDB search query in a web browser. |
| [Open-InstantStreetViewQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-instantstreetviewquery) | isv | &nbsp; |
| [Open-MovieQuote](https://github.com/genXdev/GenXdev.Queries/tree/main#open-moviequote) | moviequote | &nbsp; |
| [Open-SearchEngine](https://github.com/genXdev/GenXdev.Queries/tree/main#open-searchengine) | q | Opens a search query in the specified search engine using a web browser. |
| [Open-SimularWebSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-simularwebsiteinfo) | simularsite | &nbsp; |
| [Open-StackOverflowQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-stackoverflowquery) | qso | &nbsp; |
| [Open-Timeline](https://github.com/genXdev/GenXdev.Queries/tree/main#open-timeline) | timeline | &nbsp; |
| [Open-ViralSimulation](https://github.com/genXdev/GenXdev.Queries/tree/main#open-viralsimulation) | viral | &nbsp; |
| [Open-WaybackMachineSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-waybackmachinesiteinfo) | wayback | Opens WaybackMachine site information in a web browser. |
| [Open-WebsiteAndPerformQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-websiteandperformquery) | owaq | &nbsp; |
| [Open-WhoisHostSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-whoishostsiteinfo) | whois | &nbsp; |
| [Open-WikipediaNLQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-wikipedianlquery) | wikinl | &nbsp; |
| [Open-WikipediaQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-wikipediaquery) | wiki | &nbsp; |
| [Open-WolframAlphaQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-wolframalphaquery) | qalpha | &nbsp; |
| [Open-XGrokQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-xgrokquery) | aixg, askxgrok | &nbsp; |
| [Open-Yab](https://github.com/genXdev/GenXdev.Queries/tree/main#open-yab) | yab | Opens the YAB game in a web browser with configurable settings. |
| [Open-YabAIBattle](https://github.com/genXdev/GenXdev.Queries/tree/main#open-yabaibattle) | yabbattle | &nbsp; |
| [Open-YoutubeQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-youtubequery) | youtube | Opens YouTube search queries in a web browser. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Queries.Text

**A Windows PowerShell module for finding resources and information on the internet**

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [Clear-YoutubeWatched](https://github.com/genXdev/GenXdev.Queries/tree/main#clear-youtubewatched) | &nbsp; | Clears the YouTube watch history from the browser's local storage. |
| [ConvertTo-Uris](https://github.com/genXdev/GenXdev.Queries/tree/main#convertto-uris) | &nbsp; | Parses strings for any valid URI. |
| [Copy-PDFsFromGoogleQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#copy-pdfsfromgooglequery) | &nbsp; | Downloads PDF files found through Google search results. |
| [Get-GoogleSearchResultUrls](https://github.com/genXdev/GenXdev.Queries/tree/main#get-googlesearchresulturls) | qlinksget | Performs a google search and returns the links |
| [Get-NextAffirmation](https://github.com/genXdev/GenXdev.Queries/tree/main#get-nextaffirmation) | WhatAboutIt | Returns a random affirmation text from affirmations.dev API. |
| [Get-WikipediaSummary](https://github.com/genXdev/GenXdev.Queries/tree/main#get-wikipediasummary) | wikitxt | Retrieves a summary of a topic from Wikipedia. |
| [Invoke-WebbrowserTabPollingScript](https://github.com/genXdev/GenXdev.Queries/tree/main#invoke-webbrowsertabpollingscript) | &nbsp; | &nbsp; |
| [Open-AllGoogleLinks](https://github.com/genXdev/GenXdev.Queries/tree/main#open-allgooglelinks) | qlinks | Performs an infinite auto opening google search. |
| [Open-AllPossibleQueries](https://github.com/genXdev/GenXdev.Queries/tree/main#open-allpossiblequeries) | qq | &nbsp; |
| [Open-AllYoutubeVideos](https://github.com/genXdev/GenXdev.Queries/tree/main#open-allyoutubevideos) | qvideos, qyt | Opens and controls YouTube videos in a browser window with keyboard shortcuts. |
| [Open-BingCopilotQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-bingcopilotquery) | aibc | &nbsp; |
| [Open-BingQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-bingquery) | bq | Opens a Bing search query in a web browser. |
| [Open-BuiltWithSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-builtwithsiteinfo) | &nbsp; | Opens BuiltWith website queries in a web browser. |
| [Open-ChatGPTQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-chatgptquery) | aicgpt, askchatgpt | &nbsp; |
| [Open-CloudLLMChat](https://github.com/genXdev/GenXdev.Queries/tree/main#open-cloudllmchat) | ask | Opens a cloud LLM chat interface for AI queries. |
| [Open-DeepSearchQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-deepsearchquery) | aideepseek, askdeepsearch | &nbsp; |
| [Open-GameOfLife](https://github.com/genXdev/GenXdev.Queries/tree/main#open-gameoflife) | conway, gameoflife | &nbsp; |
| [Open-GenXdevAppCatalog](https://github.com/genXdev/GenXdev.Queries/tree/main#open-genxdevappcatalog) | appcatalog | Opens the GenXdev progressive webapps catalog in a web browser. |
| [Open-GithubCopilotQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-githubcopilotquery) | aigc, askghcopilot | &nbsp; |
| [Open-GithubQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-githubquery) | qgh, qgithub | &nbsp; |
| [Open-GoogleGeminiQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-googlegeminiquery) | aigg, askgemini | &nbsp; |
| [Open-GoogleQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-googlequery) | &nbsp; | &nbsp; |
| [Open-GoogleSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-googlesiteinfo) | &nbsp; | Opens Google site information queries in a web browser. |
| [Open-IMDBQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-imdbquery) | imdb | Opens an IMDB search query in a web browser. |
| [Open-InstantStreetViewQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-instantstreetviewquery) | isv | &nbsp; |
| [Open-MovieQuote](https://github.com/genXdev/GenXdev.Queries/tree/main#open-moviequote) | moviequote | &nbsp; |
| [Open-SearchEngine](https://github.com/genXdev/GenXdev.Queries/tree/main#open-searchengine) | q | Opens a search query in the specified search engine using a web browser. |
| [Open-SimularWebSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-simularwebsiteinfo) | simularsite | &nbsp; |
| [Open-StackOverflowQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-stackoverflowquery) | qso | &nbsp; |
| [Open-Timeline](https://github.com/genXdev/GenXdev.Queries/tree/main#open-timeline) | timeline | &nbsp; |
| [Open-ViralSimulation](https://github.com/genXdev/GenXdev.Queries/tree/main#open-viralsimulation) | viral | &nbsp; |
| [Open-WaybackMachineSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-waybackmachinesiteinfo) | wayback | Opens WaybackMachine site information in a web browser. |
| [Open-WebsiteAndPerformQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-websiteandperformquery) | owaq | &nbsp; |
| [Open-WhoisHostSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-whoishostsiteinfo) | whois | &nbsp; |
| [Open-WikipediaNLQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-wikipedianlquery) | wikinl | &nbsp; |
| [Open-WikipediaQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-wikipediaquery) | wiki | &nbsp; |
| [Open-WolframAlphaQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-wolframalphaquery) | qalpha | &nbsp; |
| [Open-XGrokQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-xgrokquery) | aixg, askxgrok | &nbsp; |
| [Open-Yab](https://github.com/genXdev/GenXdev.Queries/tree/main#open-yab) | yab | Opens the YAB game in a web browser with configurable settings. |
| [Open-YabAIBattle](https://github.com/genXdev/GenXdev.Queries/tree/main#open-yabaibattle) | yabbattle | &nbsp; |
| [Open-YoutubeQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-youtubequery) | youtube | Opens YouTube search queries in a web browser. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Queries.Webbrowser

**A Windows PowerShell module for finding resources and information on the internet**

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [Clear-YoutubeWatched](https://github.com/genXdev/GenXdev.Queries/tree/main#clear-youtubewatched) | &nbsp; | Clears the YouTube watch history from the browser's local storage. |
| [ConvertTo-Uris](https://github.com/genXdev/GenXdev.Queries/tree/main#convertto-uris) | &nbsp; | Parses strings for any valid URI. |
| [Copy-PDFsFromGoogleQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#copy-pdfsfromgooglequery) | &nbsp; | Downloads PDF files found through Google search results. |
| [Get-GoogleSearchResultUrls](https://github.com/genXdev/GenXdev.Queries/tree/main#get-googlesearchresulturls) | qlinksget | Performs a google search and returns the links |
| [Get-NextAffirmation](https://github.com/genXdev/GenXdev.Queries/tree/main#get-nextaffirmation) | WhatAboutIt | Returns a random affirmation text from affirmations.dev API. |
| [Get-WikipediaSummary](https://github.com/genXdev/GenXdev.Queries/tree/main#get-wikipediasummary) | wikitxt | Retrieves a summary of a topic from Wikipedia. |
| [Invoke-WebbrowserTabPollingScript](https://github.com/genXdev/GenXdev.Queries/tree/main#invoke-webbrowsertabpollingscript) | &nbsp; | &nbsp; |
| [Open-AllGoogleLinks](https://github.com/genXdev/GenXdev.Queries/tree/main#open-allgooglelinks) | qlinks | Performs an infinite auto opening google search. |
| [Open-AllPossibleQueries](https://github.com/genXdev/GenXdev.Queries/tree/main#open-allpossiblequeries) | qq | &nbsp; |
| [Open-AllYoutubeVideos](https://github.com/genXdev/GenXdev.Queries/tree/main#open-allyoutubevideos) | qvideos, qyt | Opens and controls YouTube videos in a browser window with keyboard shortcuts. |
| [Open-BingCopilotQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-bingcopilotquery) | aibc | &nbsp; |
| [Open-BingQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-bingquery) | bq | Opens a Bing search query in a web browser. |
| [Open-BuiltWithSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-builtwithsiteinfo) | &nbsp; | Opens BuiltWith website queries in a web browser. |
| [Open-ChatGPTQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-chatgptquery) | aicgpt, askchatgpt | &nbsp; |
| [Open-CloudLLMChat](https://github.com/genXdev/GenXdev.Queries/tree/main#open-cloudllmchat) | ask | Opens a cloud LLM chat interface for AI queries. |
| [Open-DeepSearchQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-deepsearchquery) | aideepseek, askdeepsearch | &nbsp; |
| [Open-GameOfLife](https://github.com/genXdev/GenXdev.Queries/tree/main#open-gameoflife) | conway, gameoflife | &nbsp; |
| [Open-GenXdevAppCatalog](https://github.com/genXdev/GenXdev.Queries/tree/main#open-genxdevappcatalog) | appcatalog | Opens the GenXdev progressive webapps catalog in a web browser. |
| [Open-GithubCopilotQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-githubcopilotquery) | aigc, askghcopilot | &nbsp; |
| [Open-GithubQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-githubquery) | qgh, qgithub | &nbsp; |
| [Open-GoogleGeminiQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-googlegeminiquery) | aigg, askgemini | &nbsp; |
| [Open-GoogleQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-googlequery) | &nbsp; | &nbsp; |
| [Open-GoogleSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-googlesiteinfo) | &nbsp; | Opens Google site information queries in a web browser. |
| [Open-IMDBQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-imdbquery) | imdb | Opens an IMDB search query in a web browser. |
| [Open-InstantStreetViewQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-instantstreetviewquery) | isv | &nbsp; |
| [Open-MovieQuote](https://github.com/genXdev/GenXdev.Queries/tree/main#open-moviequote) | moviequote | &nbsp; |
| [Open-SearchEngine](https://github.com/genXdev/GenXdev.Queries/tree/main#open-searchengine) | q | Opens a search query in the specified search engine using a web browser. |
| [Open-SimularWebSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-simularwebsiteinfo) | simularsite | &nbsp; |
| [Open-StackOverflowQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-stackoverflowquery) | qso | &nbsp; |
| [Open-Timeline](https://github.com/genXdev/GenXdev.Queries/tree/main#open-timeline) | timeline | &nbsp; |
| [Open-ViralSimulation](https://github.com/genXdev/GenXdev.Queries/tree/main#open-viralsimulation) | viral | &nbsp; |
| [Open-WaybackMachineSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-waybackmachinesiteinfo) | wayback | Opens WaybackMachine site information in a web browser. |
| [Open-WebsiteAndPerformQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-websiteandperformquery) | owaq | &nbsp; |
| [Open-WhoisHostSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-whoishostsiteinfo) | whois | &nbsp; |
| [Open-WikipediaNLQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-wikipedianlquery) | wikinl | &nbsp; |
| [Open-WikipediaQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-wikipediaquery) | wiki | &nbsp; |
| [Open-WolframAlphaQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-wolframalphaquery) | qalpha | &nbsp; |
| [Open-XGrokQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-xgrokquery) | aixg, askxgrok | &nbsp; |
| [Open-Yab](https://github.com/genXdev/GenXdev.Queries/tree/main#open-yab) | yab | Opens the YAB game in a web browser with configurable settings. |
| [Open-YabAIBattle](https://github.com/genXdev/GenXdev.Queries/tree/main#open-yabaibattle) | yabbattle | &nbsp; |
| [Open-YoutubeQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-youtubequery) | youtube | Opens YouTube search queries in a web browser. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Queries.Websites

**A Windows PowerShell module for finding resources and information on the internet**

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [Clear-YoutubeWatched](https://github.com/genXdev/GenXdev.Queries/tree/main#clear-youtubewatched) | &nbsp; | Clears the YouTube watch history from the browser's local storage. |
| [ConvertTo-Uris](https://github.com/genXdev/GenXdev.Queries/tree/main#convertto-uris) | &nbsp; | Parses strings for any valid URI. |
| [Copy-PDFsFromGoogleQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#copy-pdfsfromgooglequery) | &nbsp; | Downloads PDF files found through Google search results. |
| [Get-GoogleSearchResultUrls](https://github.com/genXdev/GenXdev.Queries/tree/main#get-googlesearchresulturls) | qlinksget | Performs a google search and returns the links |
| [Get-NextAffirmation](https://github.com/genXdev/GenXdev.Queries/tree/main#get-nextaffirmation) | WhatAboutIt | Returns a random affirmation text from affirmations.dev API. |
| [Get-WikipediaSummary](https://github.com/genXdev/GenXdev.Queries/tree/main#get-wikipediasummary) | wikitxt | Retrieves a summary of a topic from Wikipedia. |
| [Invoke-WebbrowserTabPollingScript](https://github.com/genXdev/GenXdev.Queries/tree/main#invoke-webbrowsertabpollingscript) | &nbsp; | &nbsp; |
| [Open-AllGoogleLinks](https://github.com/genXdev/GenXdev.Queries/tree/main#open-allgooglelinks) | qlinks | Performs an infinite auto opening google search. |
| [Open-AllPossibleQueries](https://github.com/genXdev/GenXdev.Queries/tree/main#open-allpossiblequeries) | qq | &nbsp; |
| [Open-AllYoutubeVideos](https://github.com/genXdev/GenXdev.Queries/tree/main#open-allyoutubevideos) | qvideos, qyt | Opens and controls YouTube videos in a browser window with keyboard shortcuts. |
| [Open-BingCopilotQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-bingcopilotquery) | aibc | &nbsp; |
| [Open-BingQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-bingquery) | bq | Opens a Bing search query in a web browser. |
| [Open-BuiltWithSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-builtwithsiteinfo) | &nbsp; | Opens BuiltWith website queries in a web browser. |
| [Open-ChatGPTQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-chatgptquery) | aicgpt, askchatgpt | &nbsp; |
| [Open-CloudLLMChat](https://github.com/genXdev/GenXdev.Queries/tree/main#open-cloudllmchat) | ask | Opens a cloud LLM chat interface for AI queries. |
| [Open-DeepSearchQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-deepsearchquery) | aideepseek, askdeepsearch | &nbsp; |
| [Open-GameOfLife](https://github.com/genXdev/GenXdev.Queries/tree/main#open-gameoflife) | conway, gameoflife | &nbsp; |
| [Open-GenXdevAppCatalog](https://github.com/genXdev/GenXdev.Queries/tree/main#open-genxdevappcatalog) | appcatalog | Opens the GenXdev progressive webapps catalog in a web browser. |
| [Open-GithubCopilotQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-githubcopilotquery) | aigc, askghcopilot | &nbsp; |
| [Open-GithubQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-githubquery) | qgh, qgithub | &nbsp; |
| [Open-GoogleGeminiQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-googlegeminiquery) | aigg, askgemini | &nbsp; |
| [Open-GoogleQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-googlequery) | &nbsp; | &nbsp; |
| [Open-GoogleSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-googlesiteinfo) | &nbsp; | Opens Google site information queries in a web browser. |
| [Open-IMDBQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-imdbquery) | imdb | Opens an IMDB search query in a web browser. |
| [Open-InstantStreetViewQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-instantstreetviewquery) | isv | &nbsp; |
| [Open-MovieQuote](https://github.com/genXdev/GenXdev.Queries/tree/main#open-moviequote) | moviequote | &nbsp; |
| [Open-SearchEngine](https://github.com/genXdev/GenXdev.Queries/tree/main#open-searchengine) | q | Opens a search query in the specified search engine using a web browser. |
| [Open-SimularWebSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-simularwebsiteinfo) | simularsite | &nbsp; |
| [Open-StackOverflowQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-stackoverflowquery) | qso | &nbsp; |
| [Open-Timeline](https://github.com/genXdev/GenXdev.Queries/tree/main#open-timeline) | timeline | &nbsp; |
| [Open-ViralSimulation](https://github.com/genXdev/GenXdev.Queries/tree/main#open-viralsimulation) | viral | &nbsp; |
| [Open-WaybackMachineSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-waybackmachinesiteinfo) | wayback | Opens WaybackMachine site information in a web browser. |
| [Open-WebsiteAndPerformQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-websiteandperformquery) | owaq | &nbsp; |
| [Open-WhoisHostSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-whoishostsiteinfo) | whois | &nbsp; |
| [Open-WikipediaNLQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-wikipedianlquery) | wikinl | &nbsp; |
| [Open-WikipediaQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-wikipediaquery) | wiki | &nbsp; |
| [Open-WolframAlphaQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-wolframalphaquery) | qalpha | &nbsp; |
| [Open-XGrokQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-xgrokquery) | aixg, askxgrok | &nbsp; |
| [Open-Yab](https://github.com/genXdev/GenXdev.Queries/tree/main#open-yab) | yab | Opens the YAB game in a web browser with configurable settings. |
| [Open-YabAIBattle](https://github.com/genXdev/GenXdev.Queries/tree/main#open-yabaibattle) | yabbattle | &nbsp; |
| [Open-YoutubeQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-youtubequery) | youtube | Opens YouTube search queries in a web browser. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Webbrowser

****

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [Approve-FirefoxDebugging](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#approve-firefoxdebugging) | &nbsp; | Configures Firefox's debugging and standalone app mode features. |
| [Clear-WebbrowserTabSiteApplicationData](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#clear-webbrowsertabsiteapplicationdata) | clearsitedata | Clears all browser storage data for the current tab in Edge or Chrome. |
| [Close-Webbrowser](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#close-webbrowser) | wbc | Closes one or more webbrowser instances selectively. |
| [Close-WebbrowserTab](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#close-webbrowsertab) | &nbsp; | Closes the currently selected webbrowser tab. |
| [Connect-PlaywrightViaDebuggingPort](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#connect-playwrightviadebuggingport) | &nbsp; | Connects to an existing browser instance via debugging port. |
| [Export-BrowserBookmarks](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#export-browserbookmarks) | &nbsp; | Exports browser bookmarks to a JSON file. |
| [Find-BrowserBookmark](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#find-browserbookmark) | bookmarks | Finds bookmarks from one or more web browsers. |
| [Get-BrowserBookmark](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#get-browserbookmark) | gbm | &nbsp; |
| [Get-ChromeRemoteDebuggingPort](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#get-chromeremotedebuggingport) | &nbsp; | Returns the configured remote debugging port for Google Chrome. |
| [Get-ChromiumRemoteDebuggingPort](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#get-chromiumremotedebuggingport) | &nbsp; | Returns the remote debugging port for the system's default Chromium browser. |
| [Get-ChromiumSessionReference](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#get-chromiumsessionreference) | &nbsp; | Gets a serializable reference to the current browser tab session. |
| [Get-DefaultWebbrowser](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#get-defaultwebbrowser) | &nbsp; | Returns the configured default web browser for the current user. |
| [Get-EdgeRemoteDebuggingPort](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#get-edgeremotedebuggingport) | &nbsp; | Returns the configured remote debugging port for Microsoft Edge browser. |
| [Get-PlaywrightProfileDirectory](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#get-playwrightprofiledirectory) | &nbsp; | Gets the Playwright browser profile directory for persistent sessions. |
| [Get-Webbrowser](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#get-webbrowser) | &nbsp; | Returns a collection of installed modern web browsers. |
| [Get-WebbrowserTabDomNodes](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#get-webbrowsertabdomnodes) | wl | Queries and manipulates DOM nodes in the active browser tab using CSS selectors. |
| [Import-BrowserBookmarks](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#import-browserbookmarks) | &nbsp; | &nbsp; |
| [Import-GenXdevBookmarkletMenu](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#import-genxdevbookmarkletmenu) | &nbsp; | Imports GenXdev JavaScript bookmarklets into browser bookmark collections. |
| [Invoke-WebbrowserEvaluation](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#invoke-webbrowserevaluation) | et, Eval | &nbsp; |
| [Open-BrowserBookmarks](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#open-browserbookmarks) | sites | &nbsp; |
| [Open-Webbrowser](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#open-webbrowser) | wb | &nbsp; |
| [Open-WebbrowserSideBySide](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#open-webbrowsersidebyside) | wbn | &nbsp; |
| [Resume-WebbrowserTabVideo](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#resume-webbrowsertabvideo) | wbvideoplay | Resumes video playback in a YouTube browser tab. |
| [Select-WebbrowserTab](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#select-webbrowsertab) | st | Selects a browser tab for automation in Chrome or Edge. |
| [Set-BrowserVideoFullscreen](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#set-browservideofullscreen) | fsvideo | &nbsp; |
| [Set-RemoteDebuggerPortInBrowserShortcuts](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#set-remotedebuggerportinbrowsershortcuts) | &nbsp; | Updates browser shortcuts to enable remote debugging ports. |
| [Set-WebbrowserTabLocation](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#set-webbrowsertablocation) | lt, Nav | Navigates the current webbrowser tab to a specified URL. |
| [Show-WebsiteInAllBrowsers](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#show-websiteinallbrowsers) | &nbsp; | &nbsp; |
| [Stop-WebbrowserVideos](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#stop-webbrowservideos) | ssst, wbsst, wbvideostop | Pauses video playback in all active browser sessions. |
| [Unprotect-WebbrowserTab](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#unprotect-webbrowsertab) | &nbsp; | Takes control of a selected web browser tab for interactive manipulation. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Webbrowser.Playwright

****

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [Approve-FirefoxDebugging](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#approve-firefoxdebugging) | &nbsp; | Configures Firefox's debugging and standalone app mode features. |
| [Clear-WebbrowserTabSiteApplicationData](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#clear-webbrowsertabsiteapplicationdata) | clearsitedata | Clears all browser storage data for the current tab in Edge or Chrome. |
| [Close-Webbrowser](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#close-webbrowser) | wbc | Closes one or more webbrowser instances selectively. |
| [Close-WebbrowserTab](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#close-webbrowsertab) | &nbsp; | Closes the currently selected webbrowser tab. |
| [Connect-PlaywrightViaDebuggingPort](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#connect-playwrightviadebuggingport) | &nbsp; | Connects to an existing browser instance via debugging port. |
| [Export-BrowserBookmarks](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#export-browserbookmarks) | &nbsp; | Exports browser bookmarks to a JSON file. |
| [Find-BrowserBookmark](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#find-browserbookmark) | bookmarks | Finds bookmarks from one or more web browsers. |
| [Get-BrowserBookmark](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#get-browserbookmark) | gbm | &nbsp; |
| [Get-ChromeRemoteDebuggingPort](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#get-chromeremotedebuggingport) | &nbsp; | Returns the configured remote debugging port for Google Chrome. |
| [Get-ChromiumRemoteDebuggingPort](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#get-chromiumremotedebuggingport) | &nbsp; | Returns the remote debugging port for the system's default Chromium browser. |
| [Get-ChromiumSessionReference](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#get-chromiumsessionreference) | &nbsp; | Gets a serializable reference to the current browser tab session. |
| [Get-DefaultWebbrowser](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#get-defaultwebbrowser) | &nbsp; | Returns the configured default web browser for the current user. |
| [Get-EdgeRemoteDebuggingPort](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#get-edgeremotedebuggingport) | &nbsp; | Returns the configured remote debugging port for Microsoft Edge browser. |
| [Get-PlaywrightProfileDirectory](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#get-playwrightprofiledirectory) | &nbsp; | Gets the Playwright browser profile directory for persistent sessions. |
| [Get-Webbrowser](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#get-webbrowser) | &nbsp; | Returns a collection of installed modern web browsers. |
| [Get-WebbrowserTabDomNodes](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#get-webbrowsertabdomnodes) | wl | Queries and manipulates DOM nodes in the active browser tab using CSS selectors. |
| [Import-BrowserBookmarks](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#import-browserbookmarks) | &nbsp; | &nbsp; |
| [Import-GenXdevBookmarkletMenu](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#import-genxdevbookmarkletmenu) | &nbsp; | Imports GenXdev JavaScript bookmarklets into browser bookmark collections. |
| [Invoke-WebbrowserEvaluation](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#invoke-webbrowserevaluation) | et, Eval | &nbsp; |
| [Open-BrowserBookmarks](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#open-browserbookmarks) | sites | &nbsp; |
| [Open-Webbrowser](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#open-webbrowser) | wb | &nbsp; |
| [Open-WebbrowserSideBySide](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#open-webbrowsersidebyside) | wbn | &nbsp; |
| [Resume-WebbrowserTabVideo](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#resume-webbrowsertabvideo) | wbvideoplay | Resumes video playback in a YouTube browser tab. |
| [Select-WebbrowserTab](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#select-webbrowsertab) | st | Selects a browser tab for automation in Chrome or Edge. |
| [Set-BrowserVideoFullscreen](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#set-browservideofullscreen) | fsvideo | &nbsp; |
| [Set-RemoteDebuggerPortInBrowserShortcuts](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#set-remotedebuggerportinbrowsershortcuts) | &nbsp; | Updates browser shortcuts to enable remote debugging ports. |
| [Set-WebbrowserTabLocation](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#set-webbrowsertablocation) | lt, Nav | Navigates the current webbrowser tab to a specified URL. |
| [Show-WebsiteInAllBrowsers](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#show-websiteinallbrowsers) | &nbsp; | &nbsp; |
| [Stop-WebbrowserVideos](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#stop-webbrowservideos) | ssst, wbsst, wbvideostop | Pauses video playback in all active browser sessions. |
| [Unprotect-WebbrowserTab](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#unprotect-webbrowsertab) | &nbsp; | Takes control of a selected web browser tab for interactive manipulation. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Windows

****

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [Add-WireGuardPeer](https://github.com/genXdev/GenXdev.Windows/tree/main#add-wireguardpeer) | &nbsp; | Adds a new WireGuard VPN peer (client) configuration to the server. |
| [CurrentUserHasElevatedRights](https://github.com/genXdev/GenXdev.Windows/tree/main#currentuserhaselevatedrights) | &nbsp; | &nbsp; |
| [EnsureDockerDesktop](https://github.com/genXdev/GenXdev.Windows/tree/main#ensuredockerdesktop) | &nbsp; | &nbsp; |
| [EnsurePSTools](https://github.com/genXdev/GenXdev.Windows/tree/main#ensurepstools) | &nbsp; | &nbsp; |
| [EnsureWireGuard](https://github.com/genXdev/GenXdev.Windows/tree/main#ensurewireguard) | &nbsp; | &nbsp; |
| [Get-ActiveUser](https://github.com/genXdev/GenXdev.Windows/tree/main#get-activeuser) | gusers | Retrieves a list of unique usernames from currently active system processes. |
| [Get-ChildProcesses](https://github.com/genXdev/GenXdev.Windows/tree/main#get-childprocesses) | &nbsp; | Retrieves all processes that are descendants of the current PowerShell process. |
| [Get-ClipboardFiles](https://github.com/genXdev/GenXdev.Windows/tree/main#get-clipboardfiles) | getclipfiles | Gets files from the Windows clipboard that were set for file operations like copy/paste. |
| [Get-CurrentFocusedProcess](https://github.com/genXdev/GenXdev.Windows/tree/main#get-currentfocusedprocess) | &nbsp; | Retrieves the process object of the window that currently has keyboard focus. |
| [Get-DesktopScalingFactor](https://github.com/genXdev/GenXdev.Windows/tree/main#get-desktopscalingfactor) | &nbsp; | Retrieves the Windows display scaling factor (DPI setting) for a specified monitor. |
| [Get-ForegroundWindow](https://github.com/genXdev/GenXdev.Windows/tree/main#get-foregroundwindow) | &nbsp; | Gets the handle of the currently active foreground window. |
| [Get-KnownFolderPath](https://github.com/genXdev/GenXdev.Windows/tree/main#get-knownfolderpath) | folder | Gets the path of a Windows known folder using the Windows Shell32 API. |
| [Get-MonitorCount](https://github.com/genXdev/GenXdev.Windows/tree/main#get-monitorcount) | &nbsp; | Gets the total number of display monitors connected to the system. |
| [Get-MpCmdRunPath](https://github.com/genXdev/GenXdev.Windows/tree/main#get-mpcmdrunpath) | &nbsp; | Gets the path to the Windows Defender MpCmdRun.exe executable. |
| [Get-OpenedFileHandleProcesses](https://github.com/genXdev/GenXdev.Windows/tree/main#get-openedfilehandleprocesses) | &nbsp; | Retrieves processes that have open file handles to specified files. |
| [Get-PowershellMainWindow](https://github.com/genXdev/GenXdev.Windows/tree/main#get-powershellmainwindow) | &nbsp; | Returns a window helper object for the PowerShell terminal's main window. |
| [Get-PowershellMainWindowProcess](https://github.com/genXdev/GenXdev.Windows/tree/main#get-powershellmainwindowprocess) | &nbsp; | Returns the process object for the window hosting the PowerShell terminal. |
| [Get-Window](https://github.com/genXdev/GenXdev.Windows/tree/main#get-window) | &nbsp; | Gets window information for specified processes or window handles. |
| [Get-WindowPosition](https://github.com/genXdev/GenXdev.Windows/tree/main#get-windowposition) | gwp | &nbsp; |
| [Get-WireGuardPeerQRCode](https://github.com/genXdev/GenXdev.Windows/tree/main#get-wireguardpeerqrcode) | &nbsp; | Generates a QR code for a WireGuard VPN peer configuration. |
| [Get-WireGuardPeers](https://github.com/genXdev/GenXdev.Windows/tree/main#get-wireguardpeers) | &nbsp; | &nbsp; |
| [Get-WireGuardStatus](https://github.com/genXdev/GenXdev.Windows/tree/main#get-wireguardstatus) | &nbsp; | &nbsp; |
| [Initialize-ScheduledTaskScripts](https://github.com/genXdev/GenXdev.Windows/tree/main#initialize-scheduledtaskscripts) | &nbsp; | Creates scheduled tasks that run PowerShell scripts at specified intervals. |
| [Invoke-WindowsUpdate](https://github.com/genXdev/GenXdev.Windows/tree/main#invoke-windowsupdate) | updatewindows | &nbsp; |
| [Pop-Window](https://github.com/genXdev/GenXdev.Windows/tree/main#pop-window) | popw | &nbsp; |
| [Push-Window](https://github.com/genXdev/GenXdev.Windows/tree/main#push-window) | pushw | &nbsp; |
| [Remove-WireGuardPeer](https://github.com/genXdev/GenXdev.Windows/tree/main#remove-wireguardpeer) | &nbsp; | &nbsp; |
| [Reset-WireGuardConfiguration](https://github.com/genXdev/GenXdev.Windows/tree/main#reset-wireguardconfiguration) | &nbsp; | &nbsp; |
| [Save-DesktopScreenShot](https://github.com/genXdev/GenXdev.Windows/tree/main#save-desktopscreenshot) | &nbsp; | Captures a screenshot of the specified monitor and saves it to the specified path. |
| [Send-Key](https://github.com/genXdev/GenXdev.Windows/tree/main#send-key) | invokekeys, sendkeys | &nbsp; |
| [Set-ClipboardFiles](https://github.com/genXdev/GenXdev.Windows/tree/main#set-clipboardfiles) | setclipfiles | Sets files to the Windows clipboard for file operations like copy/paste. |
| [Set-ForegroundWindow](https://github.com/genXdev/GenXdev.Windows/tree/main#set-foregroundwindow) | &nbsp; | Brings the specified window to the foreground and makes it the active window. |
| [Set-KnownFolderPath](https://github.com/genXdev/GenXdev.Windows/tree/main#set-knownfolderpath) | &nbsp; | Modifies the physical path of a Windows known folder. |
| [Set-TaskbarAlignment](https://github.com/genXdev/GenXdev.Windows/tree/main#set-taskbaralignment) | &nbsp; | Configures Windows 11+ taskbar alignment between center and left positions. |
| [Set-WindowPosition](https://github.com/genXdev/GenXdev.Windows/tree/main#set-windowposition) | wp | &nbsp; |
| [Set-WindowPositionForSecondary](https://github.com/genXdev/GenXdev.Windows/tree/main#set-windowpositionforsecondary) | wps | Positions a window on the secondary monitor with specified layout options. |
| [Set-WindowsWallpaper](https://github.com/genXdev/GenXdev.Windows/tree/main#set-windowswallpaper) | &nbsp; | Sets a random wallpaper from a specified directory. |
| [Start-ProcessWithPriority](https://github.com/genXdev/GenXdev.Windows/tree/main#start-processwithpriority) | nice | Starts a process with a specified priority level. |
| [Test-PathUsingWindowsDefender](https://github.com/genXdev/GenXdev.Windows/tree/main#test-pathusingwindowsdefender) | HasNoVirus, virusscan | Scans files or directories for malware using Windows Defender. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Windows.WireGuard

****

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [Add-WireGuardPeer](https://github.com/genXdev/GenXdev.Windows/tree/main#add-wireguardpeer) | &nbsp; | Adds a new WireGuard VPN peer (client) configuration to the server. |
| [CurrentUserHasElevatedRights](https://github.com/genXdev/GenXdev.Windows/tree/main#currentuserhaselevatedrights) | &nbsp; | &nbsp; |
| [EnsureDockerDesktop](https://github.com/genXdev/GenXdev.Windows/tree/main#ensuredockerdesktop) | &nbsp; | &nbsp; |
| [EnsurePSTools](https://github.com/genXdev/GenXdev.Windows/tree/main#ensurepstools) | &nbsp; | &nbsp; |
| [EnsureWireGuard](https://github.com/genXdev/GenXdev.Windows/tree/main#ensurewireguard) | &nbsp; | &nbsp; |
| [Get-ActiveUser](https://github.com/genXdev/GenXdev.Windows/tree/main#get-activeuser) | gusers | Retrieves a list of unique usernames from currently active system processes. |
| [Get-ChildProcesses](https://github.com/genXdev/GenXdev.Windows/tree/main#get-childprocesses) | &nbsp; | Retrieves all processes that are descendants of the current PowerShell process. |
| [Get-ClipboardFiles](https://github.com/genXdev/GenXdev.Windows/tree/main#get-clipboardfiles) | getclipfiles | Gets files from the Windows clipboard that were set for file operations like copy/paste. |
| [Get-CurrentFocusedProcess](https://github.com/genXdev/GenXdev.Windows/tree/main#get-currentfocusedprocess) | &nbsp; | Retrieves the process object of the window that currently has keyboard focus. |
| [Get-DesktopScalingFactor](https://github.com/genXdev/GenXdev.Windows/tree/main#get-desktopscalingfactor) | &nbsp; | Retrieves the Windows display scaling factor (DPI setting) for a specified monitor. |
| [Get-ForegroundWindow](https://github.com/genXdev/GenXdev.Windows/tree/main#get-foregroundwindow) | &nbsp; | Gets the handle of the currently active foreground window. |
| [Get-KnownFolderPath](https://github.com/genXdev/GenXdev.Windows/tree/main#get-knownfolderpath) | folder | Gets the path of a Windows known folder using the Windows Shell32 API. |
| [Get-MonitorCount](https://github.com/genXdev/GenXdev.Windows/tree/main#get-monitorcount) | &nbsp; | Gets the total number of display monitors connected to the system. |
| [Get-MpCmdRunPath](https://github.com/genXdev/GenXdev.Windows/tree/main#get-mpcmdrunpath) | &nbsp; | Gets the path to the Windows Defender MpCmdRun.exe executable. |
| [Get-OpenedFileHandleProcesses](https://github.com/genXdev/GenXdev.Windows/tree/main#get-openedfilehandleprocesses) | &nbsp; | Retrieves processes that have open file handles to specified files. |
| [Get-PowershellMainWindow](https://github.com/genXdev/GenXdev.Windows/tree/main#get-powershellmainwindow) | &nbsp; | Returns a window helper object for the PowerShell terminal's main window. |
| [Get-PowershellMainWindowProcess](https://github.com/genXdev/GenXdev.Windows/tree/main#get-powershellmainwindowprocess) | &nbsp; | Returns the process object for the window hosting the PowerShell terminal. |
| [Get-Window](https://github.com/genXdev/GenXdev.Windows/tree/main#get-window) | &nbsp; | Gets window information for specified processes or window handles. |
| [Get-WindowPosition](https://github.com/genXdev/GenXdev.Windows/tree/main#get-windowposition) | gwp | &nbsp; |
| [Get-WireGuardPeerQRCode](https://github.com/genXdev/GenXdev.Windows/tree/main#get-wireguardpeerqrcode) | &nbsp; | Generates a QR code for a WireGuard VPN peer configuration. |
| [Get-WireGuardPeers](https://github.com/genXdev/GenXdev.Windows/tree/main#get-wireguardpeers) | &nbsp; | &nbsp; |
| [Get-WireGuardStatus](https://github.com/genXdev/GenXdev.Windows/tree/main#get-wireguardstatus) | &nbsp; | &nbsp; |
| [Initialize-ScheduledTaskScripts](https://github.com/genXdev/GenXdev.Windows/tree/main#initialize-scheduledtaskscripts) | &nbsp; | Creates scheduled tasks that run PowerShell scripts at specified intervals. |
| [Invoke-WindowsUpdate](https://github.com/genXdev/GenXdev.Windows/tree/main#invoke-windowsupdate) | updatewindows | &nbsp; |
| [Pop-Window](https://github.com/genXdev/GenXdev.Windows/tree/main#pop-window) | popw | &nbsp; |
| [Push-Window](https://github.com/genXdev/GenXdev.Windows/tree/main#push-window) | pushw | &nbsp; |
| [Remove-WireGuardPeer](https://github.com/genXdev/GenXdev.Windows/tree/main#remove-wireguardpeer) | &nbsp; | &nbsp; |
| [Reset-WireGuardConfiguration](https://github.com/genXdev/GenXdev.Windows/tree/main#reset-wireguardconfiguration) | &nbsp; | &nbsp; |
| [Save-DesktopScreenShot](https://github.com/genXdev/GenXdev.Windows/tree/main#save-desktopscreenshot) | &nbsp; | Captures a screenshot of the specified monitor and saves it to the specified path. |
| [Send-Key](https://github.com/genXdev/GenXdev.Windows/tree/main#send-key) | invokekeys, sendkeys | &nbsp; |
| [Set-ClipboardFiles](https://github.com/genXdev/GenXdev.Windows/tree/main#set-clipboardfiles) | setclipfiles | Sets files to the Windows clipboard for file operations like copy/paste. |
| [Set-ForegroundWindow](https://github.com/genXdev/GenXdev.Windows/tree/main#set-foregroundwindow) | &nbsp; | Brings the specified window to the foreground and makes it the active window. |
| [Set-KnownFolderPath](https://github.com/genXdev/GenXdev.Windows/tree/main#set-knownfolderpath) | &nbsp; | Modifies the physical path of a Windows known folder. |
| [Set-TaskbarAlignment](https://github.com/genXdev/GenXdev.Windows/tree/main#set-taskbaralignment) | &nbsp; | Configures Windows 11+ taskbar alignment between center and left positions. |
| [Set-WindowPosition](https://github.com/genXdev/GenXdev.Windows/tree/main#set-windowposition) | wp | &nbsp; |
| [Set-WindowPositionForSecondary](https://github.com/genXdev/GenXdev.Windows/tree/main#set-windowpositionforsecondary) | wps | Positions a window on the secondary monitor with specified layout options. |
| [Set-WindowsWallpaper](https://github.com/genXdev/GenXdev.Windows/tree/main#set-windowswallpaper) | &nbsp; | Sets a random wallpaper from a specified directory. |
| [Start-ProcessWithPriority](https://github.com/genXdev/GenXdev.Windows/tree/main#start-processwithpriority) | nice | Starts a process with a specified priority level. |
| [Test-PathUsingWindowsDefender](https://github.com/genXdev/GenXdev.Windows/tree/main#test-pathusingwindowsdefender) | HasNoVirus, virusscan | Scans files or directories for malware using Windows Defender. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

