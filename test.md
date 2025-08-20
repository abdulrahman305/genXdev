<hr/>

<img src="powershell.jpg" alt="GenXdev" width="50%"/>

<hr/>

### NAME
    GenXdev Powershell Modules
### SYNOPSIS
    GenXdev PowerShell Utilities and helpers
[![GenXdev](https://img.shields.io/powershellgallery/v/GenXdev.svg?style=flat-square&label=GenXdev)](https://www.powershellgallery.com/packages/GenXdev/) [![License](https://img.shields.io/github/license/genXdev/GenXdev?style=flat-square)](./LICENSE)

## MIT License

````text
MIT License

Copyright (c) 2025 GenXdev

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
````

# Modules

## Module Overview

| Module | Description | Repository |
| --- | --- | --- |
| [GenXdev.AI](#genxdevai) | A Windows PowerShell module for local AI related operations | [📁 GenXdev.AI](https://github.com/genXdev/GenXdev.AI) |
| [GenXdev.Coding](#genxdevcoding) | A Windows PowerShell module that helps being more productive with coding tasks. | [📁 GenXdev.Coding](https://github.com/genXdev/GenXdev.Coding) |
| [GenXdev.Console](#genxdevconsole) | A Windows PowerShell module for enhancing the commandline experience | [📁 GenXdev.Console](https://github.com/genXdev/GenXdev.Console) |
| [GenXdev.Data](#genxdevdata) | A Windows PowerShell module for enhancing the commandline experience | [📁 GenXdev.Data](https://github.com/genXdev/GenXdev.Data) |
| [GenXdev.FileSystem](#genxdevfilesystem) | A Windows PowerShell module for basic and advanced file management tasks | [📁 GenXdev.FileSystem](https://github.com/genXdev/GenXdev.FileSystem) |
| [GenXdev.Helpers](#genxdevhelpers) | A Windows PowerShell module with helpers mostly used by other GenXdev modules | [📁 GenXdev.Helpers](https://github.com/genXdev/GenXdev.Helpers) |
| [GenXdev.Media](#genxdevmedia) | A Windows PowerShell module that helps with converting media files like pictures and video files | [📁 GenXdev.Media](https://github.com/genXdev/GenXdev.Media) |
| [GenXdev.Queries](#genxdevqueries) | A Windows PowerShell module for finding resources and information on the internet | [📁 GenXdev.Queries](https://github.com/genXdev/GenXdev.Queries) |
| [GenXdev.Webbrowser](#genxdevwebbrowser) | PowerShell module for webbrowser operations | [📁 GenXdev.Webbrowser](https://github.com/genXdev/GenXdev.Webbrowser) |
| [GenXdev.Windows](#genxdevwindows) | PowerShell module for windows operations | [📁 GenXdev.Windows](https://github.com/genXdev/GenXdev.Windows) |

<br/><hr/><br/>

## GenXdev.AI

**A Windows PowerShell module for local AI related operations**

### Cmdlet Index

| Command | Aliases | Description |
| --- | --- | --- |
| [Add-EmoticonsToText](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#add-emoticonstotext) | emojify | Enhances text by adding contextually appropriate emoticons using AI. |
| [Add-GenXdevMCPServerToLMStudio](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#add-genxdevmcpservertolmstudio) | &nbsp; | Adds the GenXdev MCP server to LM Studio using a deeplink configuration. |
| [Add-ImageDirectories](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#add-imagedirectories) | addimgdir | Adds directories to the configured image directories for GenXdev.AI operations. |
| [Approve-NewTextFileContent](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#approve-newtextfilecontent) | &nbsp; | Interactive file content comparison and approval using WinMerge. |
| [Compare-ImageFaces](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#compare-imagefaces) | comparefaces | Processes the face match result from DeepStack API. |
| [Convert-DotNetTypeToLLMType](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#convert-dotnettypetollmtype) | &nbsp; | Converts .NET type names to LLM (Language Model) type names. |
| [ConvertFrom-CorporateSpeak](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#convertfrom-corporatespeak) | uncorporatize | Converts polite, professional corporate speak into direct, clear language using AI. |
| [ConvertFrom-DiplomaticSpeak](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#convertfrom-diplomaticspeak) | undiplomatize | &nbsp; |
| [ConvertTo-CorporateSpeak](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#convertto-corporatespeak) | corporatize | Converts direct or blunt text into polite, professional corporate speak using AI. |
| [ConvertTo-DiplomaticSpeak](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#convertto-diplomaticspeak) | diplomatize | Converts direct or blunt text into polite, tactful diplomatic language. |
| [ConvertTo-LMStudioFunctionDefinition](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#convertto-lmstudiofunctiondefinition) | &nbsp; | Converts PowerShell functions to LMStudio function definitions. |
| [EnsureDeepStack](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#ensuredeepstack) | &nbsp; | Ensures DeepStack face recognition service is installed and running. |
| [EnsureGithubCLIInstalled](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#ensuregithubcliinstalled) | &nbsp; | Ensures GitHub CLI is properly installed and configured on the system. |
| [EnsureLMStudio](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#ensurelmstudio) | &nbsp; | Ensures LM Studio is properly initialized with the specified model. |
| [EnsurePaintNet](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#ensurepaintnet) | &nbsp; | Ensures Paint.NET is properly installed and accessible on the system. |
| [EnsureWinMergeInstalled](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#ensurewinmergeinstalled) | &nbsp; | Ensures WinMerge is installed and available for file comparison operations. |
| [Export-ImageIndex](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#export-imageindex) | indeximages | Initializes and populates the SQLite database by discovering images directly. |
| [Find-Image](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#find-image) | findimages, li | &nbsp; |
| [Find-IndexedImage](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#find-indexedimage) | findindexedimages, lii | Searches for images using an optimized SQLite database with fast indexed lookups. |
| [GenerateMasonryLayoutHtml](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#generatemasonrylayouthtml) | &nbsp; | Generates a responsive masonry layout HTML gallery from image data. |
| [Get-AIDefaultLLMSettings](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-aidefaultllmsettings) | &nbsp; | Gets all available default LLM settings configurations for AI operations in GenXdev.AI. |
| [Get-AIImageCollection](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-aiimagecollection) | getimgdirs | Gets the configured directories for image files used in GenXdev.AI operations. |
| [Get-AIKnownFacesRootpath](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-aiknownfacesrootpath) | &nbsp; | &nbsp; |
| [Get-AILLMSettings](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-aillmsettings) | &nbsp; | Gets the LLM settings for AI operations in GenXdev.AI. |
| [Get-AIMetaLanguage](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-aimetalanguage) | getimgmetalang | Gets the configured default language for image metadata operations. |
| [Get-CpuCore](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-cpucore) | &nbsp; | Calculates and returns the total number of logical CPU cores in the system. |
| [Get-Fallacy](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-fallacy) | dispicetext | Analyzes text to identify logical fallacies using AI-powered detection. |
| [Get-HasCapableGpu](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-hascapablegpu) | &nbsp; | Determines if a CUDA-capable GPU with sufficient memory is present. |
| [Get-ImageDetectedFaces](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-imagedetectedfaces) | &nbsp; | &nbsp; |
| [Get-ImageDetectedObjects](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-imagedetectedobjects) | &nbsp; | Detects and classifies objects in an uploaded image using DeepStack. |
| [Get-ImageDetectedScenes](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-imagedetectedscenes) | &nbsp; | Classifies an image into one of 365 scene categories using DeepStack. |
| [Get-ImageIndexPath](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-imageindexpath) | &nbsp; | Returns the path to the image database, initializing or rebuilding it if needed. |
| [Get-ImageIndexStats](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-imageindexstats) | getimagedbstats, gids | Retrieves comprehensive statistics and information about the image database. |
| [Get-LMStudioLoadedModelList](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-lmstudioloadedmodellist) | &nbsp; | Retrieves the list of currently loaded models from LM Studio. |
| [Get-LMStudioModelList](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-lmstudiomodellist) | &nbsp; | Retrieves a list of installed LM Studio models. |
| [Get-LMStudioPaths](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-lmstudiopaths) | &nbsp; | Retrieves file paths for LM Studio executables. |
| [Get-LMStudioTextEmbedding](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-lmstudiotextembedding) | embed-text, Get-TextEmbedding | Gets text embeddings from LM Studio model. |
| [Get-LMStudioWindow](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-lmstudiowindow) | lmstudiowindow, setlmstudiowindow | Gets a window helper for the LM Studio application. |
| [Get-MediaFileAudioTranscription](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-mediafileaudiotranscription) | transcribefile | Transcribes an audio or video file to text. |
| [Get-NumberOfCpuCores](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-numberofcpucores) | &nbsp; | Calculates and returns the total number of logical CPU cores in the system. |
| [Get-RegisteredFaces](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-registeredfaces) | &nbsp; | Retrieves a list of all registered face identifiers from DeepStack. |
| [Get-ScriptExecutionErrorFixPrompt](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-scriptexecutionerrorfixprompt) | getfixprompt | Captures error messages from various streams and uses LLM to suggest fixes. |
| [Get-SimularMovieTitles](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-simularmovietitles) | &nbsp; | Finds similar movie titles based on common properties. |
| [Get-TextTranslation](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-texttranslation) | translate | Translates text to another language using AI. |
| [Get-VectorSimilarity](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-vectorsimilarity) | &nbsp; | &nbsp; |
| [Initialize-LMStudioModel](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#initialize-lmstudiomodel) | initlmstudio | Initializes and loads an AI model in LM Studio. |
| [Install-LMStudioApplication](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#install-lmstudioapplication) | &nbsp; | Installs LM Studio application using WinGet package manager. |
| [Invoke-AIPowershellCommand](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-aipowershellcommand) | hint | Converts AI command suggestions to JSON format for processing. |
| [Invoke-CommandFromToolCall](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-commandfromtoolcall) | &nbsp; | Executes a tool call function with validation and parameter filtering. |
| [Invoke-ImageEnhancement](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-imageenhancement) | enhanceimage | Enhances an image by enlarging it 4X while improving quality using DeepStack. |
| [Invoke-ImageFacesUpdate](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-imagefacesupdate) | imagepeopledetection | Updates face recognition metadata for image files in a specified directory. |
| [Invoke-ImageKeywordUpdate](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-imagekeywordupdate) | imagekeywordgeneration | Updates image metadata with AI-generated descriptions and keywords. |
| [Invoke-ImageMetadataUpdate](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-imagemetadataupdate) | imagepropdetection | Updates EXIF metadata for images in a directory. |
| [Invoke-ImageObjectsUpdate](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-imageobjectsupdate) | imageobjectdetection | Updates object detection metadata for image files in a specified directory. |
| [Invoke-ImageScenesUpdate](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-imagescenesupdate) | imagescenedetection | Updates scene classification metadata for image files in a specified directory. |
| [Invoke-LLMBooleanEvaluation](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-llmbooleanevaluation) | equalstrue | Evaluates a statement using AI to determine if it's true or false. |
| [Invoke-LLMQuery](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-llmquery) | Invoke-LMStudioQuery, llm, qllm, qlms | &nbsp; |
| [Invoke-LLMStringListEvaluation](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-llmstringlistevaluation) | getlist, getstring | &nbsp; |
| [Invoke-LLMTextTransformation](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-llmtexttransformation) | spellcheck | Transforms text using AI-powered processing. |
| [Invoke-QueryImageContent](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-queryimagecontent) | Query-Image | Analyzes image content using AI vision capabilities through the LM-Studio API. |
| [Invoke-WinMerge](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-winmerge) | &nbsp; | Launches WinMerge to compare two files side by side. |
| [New-LLMAudioChat](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#new-llmaudiochat) | llmaudiochat | Creates an interactive audio chat session with an LLM model. |
| [New-LLMTextChat](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#new-llmtextchat) | llmchat | Starts an interactive text chat session with AI capabilities. |
| [Register-AllFaces](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#register-allfaces) | UpdateFaces | Updates all face recognition profiles from image files in the faces directory. |
| [Register-Face](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#register-face) | &nbsp; | Registers a new face with the DeepStack face recognition API. |
| [Remove-ImageDirectories](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#remove-imagedirectories) | removeimgdir | Removes directories from the configured image directories for GenXdev.AI operations. |
| [Remove-ImageMetaData](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#remove-imagemetadata) | removeimagedata | Removes image metadata files from image directories. |
| [Save-FoundImageFaces](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#save-foundimagefaces) | saveimagefaces | Saves cropped face images from indexed image search results. |
| [Save-FoundImageObjects](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#save-foundimageobjects) | saveimageObjects | Saves cropped object images from indexed image search results to files. |
| [Save-Transcriptions](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#save-transcriptions) | &nbsp; | Generates subtitle files for audio and video files using OpenAI Whisper. |
| [Set-AIImageCollection](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#set-aiimagecollection) | &nbsp; | &nbsp; |
| [Set-AIKnownFacesRootpath](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#set-aiknownfacesrootpath) | &nbsp; | Sets the directory for face image files used in GenXdev.AI operations. |
| [Set-AILLMSettings](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#set-aillmsettings) | &nbsp; | Sets the LLM settings for AI operations in GenXdev.AI. |
| [Set-AIMetaLanguage](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#set-aimetalanguage) | &nbsp; | &nbsp; |
| [Set-GenXdevAICommandNotFoundAction](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#set-genxdevaicommandnotfoundaction) | &nbsp; | Sets up custom command not found handling with AI assistance. |
| [Set-ImageIndexPath](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#set-imageindexpath) | &nbsp; | Sets the default database file path for image operations in GenXdev.AI. |
| [Set-WindowsWallpaperEx](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#set-windowswallpaperex) | nextwallpaper | Sets a random wallpaper from a specified directory or search criteria. |
| [Show-FoundImagesInBrowser](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#show-foundimagesinbrowser) | showfoundimages | Displays image search results in a masonry layout web gallery. |
| [Show-GenXdevScriptErrorFixInIde](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#show-genxdevscripterrorfixinide) | letsfixthis | Executes a script block and analyzes errors using AI to generate fixes in IDE. |
| [Start-AudioTranscription](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#start-audiotranscription) | recordandtranscribe, transcribe | &nbsp; |
| [Start-GenXdevMCPServer](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#start-genxdevmcpserver) | &nbsp; | Starts the GenXdev MCP server that exposes PowerShell cmdlets as tools. |
| [Start-LMStudioApplication](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#start-lmstudioapplication) | &nbsp; | Starts the LM Studio application if it's not already running. |
| [Test-DeepLinkImageFile](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#test-deeplinkimagefile) | &nbsp; | Tests if the specified file path is a valid image file with a supported format. |
| [Test-LMStudioInstallation](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#test-lmstudioinstallation) | &nbsp; | Tests if LMStudio is installed and accessible on the system. |
| [Test-LMStudioProcess](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#test-lmstudioprocess) | &nbsp; | Tests if LM Studio process is running and configures its window state. |
| [Unregister-AllFaces](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#unregister-allfaces) | &nbsp; | Removes all registered faces from the DeepStack face recognition system. |
| [Unregister-Face](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#unregister-face) | &nbsp; | Deletes a registered face by its identifier from DeepStack. |
| [Update-AllImageMetaData](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#update-allimagemetadata) | updateallimages | &nbsp; |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.AI/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.AI.Data

**A Windows PowerShell module for local AI related operations**

### Cmdlet Index

| Command | Aliases | Description |
| --- | --- | --- |
| [Add-EmoticonsToText](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#add-emoticonstotext) | emojify | Enhances text by adding contextually appropriate emoticons using AI. |
| [Add-GenXdevMCPServerToLMStudio](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#add-genxdevmcpservertolmstudio) | &nbsp; | Adds the GenXdev MCP server to LM Studio using a deeplink configuration. |
| [Add-ImageDirectories](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#add-imagedirectories) | addimgdir | Adds directories to the configured image directories for GenXdev.AI operations. |
| [Approve-NewTextFileContent](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#approve-newtextfilecontent) | &nbsp; | Interactive file content comparison and approval using WinMerge. |
| [Compare-ImageFaces](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#compare-imagefaces) | comparefaces | Processes the face match result from DeepStack API. |
| [Convert-DotNetTypeToLLMType](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#convert-dotnettypetollmtype) | &nbsp; | Converts .NET type names to LLM (Language Model) type names. |
| [ConvertFrom-CorporateSpeak](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#convertfrom-corporatespeak) | uncorporatize | Converts polite, professional corporate speak into direct, clear language using AI. |
| [ConvertFrom-DiplomaticSpeak](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#convertfrom-diplomaticspeak) | undiplomatize | &nbsp; |
| [ConvertTo-CorporateSpeak](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#convertto-corporatespeak) | corporatize | Converts direct or blunt text into polite, professional corporate speak using AI. |
| [ConvertTo-DiplomaticSpeak](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#convertto-diplomaticspeak) | diplomatize | Converts direct or blunt text into polite, tactful diplomatic language. |
| [ConvertTo-LMStudioFunctionDefinition](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#convertto-lmstudiofunctiondefinition) | &nbsp; | Converts PowerShell functions to LMStudio function definitions. |
| [EnsureDeepStack](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#ensuredeepstack) | &nbsp; | Ensures DeepStack face recognition service is installed and running. |
| [EnsureGithubCLIInstalled](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#ensuregithubcliinstalled) | &nbsp; | Ensures GitHub CLI is properly installed and configured on the system. |
| [EnsureLMStudio](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#ensurelmstudio) | &nbsp; | Ensures LM Studio is properly initialized with the specified model. |
| [EnsurePaintNet](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#ensurepaintnet) | &nbsp; | Ensures Paint.NET is properly installed and accessible on the system. |
| [EnsureWinMergeInstalled](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#ensurewinmergeinstalled) | &nbsp; | Ensures WinMerge is installed and available for file comparison operations. |
| [Export-ImageIndex](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#export-imageindex) | indeximages | Initializes and populates the SQLite database by discovering images directly. |
| [Find-Image](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#find-image) | findimages, li | &nbsp; |
| [Find-IndexedImage](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#find-indexedimage) | findindexedimages, lii | Searches for images using an optimized SQLite database with fast indexed lookups. |
| [GenerateMasonryLayoutHtml](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#generatemasonrylayouthtml) | &nbsp; | Generates a responsive masonry layout HTML gallery from image data. |
| [Get-AIDefaultLLMSettings](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-aidefaultllmsettings) | &nbsp; | Gets all available default LLM settings configurations for AI operations in GenXdev.AI. |
| [Get-AIImageCollection](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-aiimagecollection) | getimgdirs | Gets the configured directories for image files used in GenXdev.AI operations. |
| [Get-AIKnownFacesRootpath](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-aiknownfacesrootpath) | &nbsp; | &nbsp; |
| [Get-AILLMSettings](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-aillmsettings) | &nbsp; | Gets the LLM settings for AI operations in GenXdev.AI. |
| [Get-AIMetaLanguage](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-aimetalanguage) | getimgmetalang | Gets the configured default language for image metadata operations. |
| [Get-CpuCore](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-cpucore) | &nbsp; | Calculates and returns the total number of logical CPU cores in the system. |
| [Get-Fallacy](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-fallacy) | dispicetext | Analyzes text to identify logical fallacies using AI-powered detection. |
| [Get-HasCapableGpu](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-hascapablegpu) | &nbsp; | Determines if a CUDA-capable GPU with sufficient memory is present. |
| [Get-ImageDetectedFaces](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-imagedetectedfaces) | &nbsp; | &nbsp; |
| [Get-ImageDetectedObjects](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-imagedetectedobjects) | &nbsp; | Detects and classifies objects in an uploaded image using DeepStack. |
| [Get-ImageDetectedScenes](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-imagedetectedscenes) | &nbsp; | Classifies an image into one of 365 scene categories using DeepStack. |
| [Get-ImageIndexPath](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-imageindexpath) | &nbsp; | Returns the path to the image database, initializing or rebuilding it if needed. |
| [Get-ImageIndexStats](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-imageindexstats) | getimagedbstats, gids | Retrieves comprehensive statistics and information about the image database. |
| [Get-LMStudioLoadedModelList](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-lmstudioloadedmodellist) | &nbsp; | Retrieves the list of currently loaded models from LM Studio. |
| [Get-LMStudioModelList](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-lmstudiomodellist) | &nbsp; | Retrieves a list of installed LM Studio models. |
| [Get-LMStudioPaths](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-lmstudiopaths) | &nbsp; | Retrieves file paths for LM Studio executables. |
| [Get-LMStudioTextEmbedding](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-lmstudiotextembedding) | embed-text, Get-TextEmbedding | Gets text embeddings from LM Studio model. |
| [Get-LMStudioWindow](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-lmstudiowindow) | lmstudiowindow, setlmstudiowindow | Gets a window helper for the LM Studio application. |
| [Get-MediaFileAudioTranscription](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-mediafileaudiotranscription) | transcribefile | Transcribes an audio or video file to text. |
| [Get-NumberOfCpuCores](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-numberofcpucores) | &nbsp; | Calculates and returns the total number of logical CPU cores in the system. |
| [Get-RegisteredFaces](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-registeredfaces) | &nbsp; | Retrieves a list of all registered face identifiers from DeepStack. |
| [Get-ScriptExecutionErrorFixPrompt](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-scriptexecutionerrorfixprompt) | getfixprompt | Captures error messages from various streams and uses LLM to suggest fixes. |
| [Get-SimularMovieTitles](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-simularmovietitles) | &nbsp; | Finds similar movie titles based on common properties. |
| [Get-TextTranslation](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-texttranslation) | translate | Translates text to another language using AI. |
| [Get-VectorSimilarity](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-vectorsimilarity) | &nbsp; | &nbsp; |
| [Initialize-LMStudioModel](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#initialize-lmstudiomodel) | initlmstudio | Initializes and loads an AI model in LM Studio. |
| [Install-LMStudioApplication](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#install-lmstudioapplication) | &nbsp; | Installs LM Studio application using WinGet package manager. |
| [Invoke-AIPowershellCommand](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-aipowershellcommand) | hint | Converts AI command suggestions to JSON format for processing. |
| [Invoke-CommandFromToolCall](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-commandfromtoolcall) | &nbsp; | Executes a tool call function with validation and parameter filtering. |
| [Invoke-ImageEnhancement](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-imageenhancement) | enhanceimage | Enhances an image by enlarging it 4X while improving quality using DeepStack. |
| [Invoke-ImageFacesUpdate](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-imagefacesupdate) | imagepeopledetection | Updates face recognition metadata for image files in a specified directory. |
| [Invoke-ImageKeywordUpdate](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-imagekeywordupdate) | imagekeywordgeneration | Updates image metadata with AI-generated descriptions and keywords. |
| [Invoke-ImageMetadataUpdate](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-imagemetadataupdate) | imagepropdetection | Updates EXIF metadata for images in a directory. |
| [Invoke-ImageObjectsUpdate](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-imageobjectsupdate) | imageobjectdetection | Updates object detection metadata for image files in a specified directory. |
| [Invoke-ImageScenesUpdate](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-imagescenesupdate) | imagescenedetection | Updates scene classification metadata for image files in a specified directory. |
| [Invoke-LLMBooleanEvaluation](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-llmbooleanevaluation) | equalstrue | Evaluates a statement using AI to determine if it's true or false. |
| [Invoke-LLMQuery](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-llmquery) | Invoke-LMStudioQuery, llm, qllm, qlms | &nbsp; |
| [Invoke-LLMStringListEvaluation](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-llmstringlistevaluation) | getlist, getstring | &nbsp; |
| [Invoke-LLMTextTransformation](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-llmtexttransformation) | spellcheck | Transforms text using AI-powered processing. |
| [Invoke-QueryImageContent](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-queryimagecontent) | Query-Image | Analyzes image content using AI vision capabilities through the LM-Studio API. |
| [Invoke-WinMerge](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-winmerge) | &nbsp; | Launches WinMerge to compare two files side by side. |
| [New-LLMAudioChat](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#new-llmaudiochat) | llmaudiochat | Creates an interactive audio chat session with an LLM model. |
| [New-LLMTextChat](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#new-llmtextchat) | llmchat | Starts an interactive text chat session with AI capabilities. |
| [Register-AllFaces](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#register-allfaces) | UpdateFaces | Updates all face recognition profiles from image files in the faces directory. |
| [Register-Face](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#register-face) | &nbsp; | Registers a new face with the DeepStack face recognition API. |
| [Remove-ImageDirectories](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#remove-imagedirectories) | removeimgdir | Removes directories from the configured image directories for GenXdev.AI operations. |
| [Remove-ImageMetaData](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#remove-imagemetadata) | removeimagedata | Removes image metadata files from image directories. |
| [Save-FoundImageFaces](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#save-foundimagefaces) | saveimagefaces | Saves cropped face images from indexed image search results. |
| [Save-FoundImageObjects](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#save-foundimageobjects) | saveimageObjects | Saves cropped object images from indexed image search results to files. |
| [Save-Transcriptions](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#save-transcriptions) | &nbsp; | Generates subtitle files for audio and video files using OpenAI Whisper. |
| [Set-AIImageCollection](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#set-aiimagecollection) | &nbsp; | &nbsp; |
| [Set-AIKnownFacesRootpath](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#set-aiknownfacesrootpath) | &nbsp; | Sets the directory for face image files used in GenXdev.AI operations. |
| [Set-AILLMSettings](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#set-aillmsettings) | &nbsp; | Sets the LLM settings for AI operations in GenXdev.AI. |
| [Set-AIMetaLanguage](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#set-aimetalanguage) | &nbsp; | &nbsp; |
| [Set-GenXdevAICommandNotFoundAction](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#set-genxdevaicommandnotfoundaction) | &nbsp; | Sets up custom command not found handling with AI assistance. |
| [Set-ImageIndexPath](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#set-imageindexpath) | &nbsp; | Sets the default database file path for image operations in GenXdev.AI. |
| [Set-WindowsWallpaperEx](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#set-windowswallpaperex) | nextwallpaper | Sets a random wallpaper from a specified directory or search criteria. |
| [Show-FoundImagesInBrowser](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#show-foundimagesinbrowser) | showfoundimages | Displays image search results in a masonry layout web gallery. |
| [Show-GenXdevScriptErrorFixInIde](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#show-genxdevscripterrorfixinide) | letsfixthis | Executes a script block and analyzes errors using AI to generate fixes in IDE. |
| [Start-AudioTranscription](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#start-audiotranscription) | recordandtranscribe, transcribe | &nbsp; |
| [Start-GenXdevMCPServer](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#start-genxdevmcpserver) | &nbsp; | Starts the GenXdev MCP server that exposes PowerShell cmdlets as tools. |
| [Start-LMStudioApplication](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#start-lmstudioapplication) | &nbsp; | Starts the LM Studio application if it's not already running. |
| [Test-DeepLinkImageFile](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#test-deeplinkimagefile) | &nbsp; | Tests if the specified file path is a valid image file with a supported format. |
| [Test-LMStudioInstallation](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#test-lmstudioinstallation) | &nbsp; | Tests if LMStudio is installed and accessible on the system. |
| [Test-LMStudioProcess](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#test-lmstudioprocess) | &nbsp; | Tests if LM Studio process is running and configures its window state. |
| [Unregister-AllFaces](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#unregister-allfaces) | &nbsp; | Removes all registered faces from the DeepStack face recognition system. |
| [Unregister-Face](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#unregister-face) | &nbsp; | Deletes a registered face by its identifier from DeepStack. |
| [Update-AllImageMetaData](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#update-allimagemetadata) | updateallimages | &nbsp; |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.AI/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.AI.DeepStack

**A Windows PowerShell module for local AI related operations**

### Cmdlet Index

| Command | Aliases | Description |
| --- | --- | --- |
| [Add-EmoticonsToText](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#add-emoticonstotext) | emojify | Enhances text by adding contextually appropriate emoticons using AI. |
| [Add-GenXdevMCPServerToLMStudio](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#add-genxdevmcpservertolmstudio) | &nbsp; | Adds the GenXdev MCP server to LM Studio using a deeplink configuration. |
| [Add-ImageDirectories](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#add-imagedirectories) | addimgdir | Adds directories to the configured image directories for GenXdev.AI operations. |
| [Approve-NewTextFileContent](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#approve-newtextfilecontent) | &nbsp; | Interactive file content comparison and approval using WinMerge. |
| [Compare-ImageFaces](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#compare-imagefaces) | comparefaces | Processes the face match result from DeepStack API. |
| [Convert-DotNetTypeToLLMType](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#convert-dotnettypetollmtype) | &nbsp; | Converts .NET type names to LLM (Language Model) type names. |
| [ConvertFrom-CorporateSpeak](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#convertfrom-corporatespeak) | uncorporatize | Converts polite, professional corporate speak into direct, clear language using AI. |
| [ConvertFrom-DiplomaticSpeak](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#convertfrom-diplomaticspeak) | undiplomatize | &nbsp; |
| [ConvertTo-CorporateSpeak](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#convertto-corporatespeak) | corporatize | Converts direct or blunt text into polite, professional corporate speak using AI. |
| [ConvertTo-DiplomaticSpeak](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#convertto-diplomaticspeak) | diplomatize | Converts direct or blunt text into polite, tactful diplomatic language. |
| [ConvertTo-LMStudioFunctionDefinition](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#convertto-lmstudiofunctiondefinition) | &nbsp; | Converts PowerShell functions to LMStudio function definitions. |
| [EnsureDeepStack](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#ensuredeepstack) | &nbsp; | Ensures DeepStack face recognition service is installed and running. |
| [EnsureGithubCLIInstalled](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#ensuregithubcliinstalled) | &nbsp; | Ensures GitHub CLI is properly installed and configured on the system. |
| [EnsureLMStudio](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#ensurelmstudio) | &nbsp; | Ensures LM Studio is properly initialized with the specified model. |
| [EnsurePaintNet](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#ensurepaintnet) | &nbsp; | Ensures Paint.NET is properly installed and accessible on the system. |
| [EnsureWinMergeInstalled](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#ensurewinmergeinstalled) | &nbsp; | Ensures WinMerge is installed and available for file comparison operations. |
| [Export-ImageIndex](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#export-imageindex) | indeximages | Initializes and populates the SQLite database by discovering images directly. |
| [Find-Image](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#find-image) | findimages, li | &nbsp; |
| [Find-IndexedImage](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#find-indexedimage) | findindexedimages, lii | Searches for images using an optimized SQLite database with fast indexed lookups. |
| [GenerateMasonryLayoutHtml](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#generatemasonrylayouthtml) | &nbsp; | Generates a responsive masonry layout HTML gallery from image data. |
| [Get-AIDefaultLLMSettings](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-aidefaultllmsettings) | &nbsp; | Gets all available default LLM settings configurations for AI operations in GenXdev.AI. |
| [Get-AIImageCollection](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-aiimagecollection) | getimgdirs | Gets the configured directories for image files used in GenXdev.AI operations. |
| [Get-AIKnownFacesRootpath](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-aiknownfacesrootpath) | &nbsp; | &nbsp; |
| [Get-AILLMSettings](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-aillmsettings) | &nbsp; | Gets the LLM settings for AI operations in GenXdev.AI. |
| [Get-AIMetaLanguage](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-aimetalanguage) | getimgmetalang | Gets the configured default language for image metadata operations. |
| [Get-CpuCore](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-cpucore) | &nbsp; | Calculates and returns the total number of logical CPU cores in the system. |
| [Get-Fallacy](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-fallacy) | dispicetext | Analyzes text to identify logical fallacies using AI-powered detection. |
| [Get-HasCapableGpu](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-hascapablegpu) | &nbsp; | Determines if a CUDA-capable GPU with sufficient memory is present. |
| [Get-ImageDetectedFaces](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-imagedetectedfaces) | &nbsp; | &nbsp; |
| [Get-ImageDetectedObjects](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-imagedetectedobjects) | &nbsp; | Detects and classifies objects in an uploaded image using DeepStack. |
| [Get-ImageDetectedScenes](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-imagedetectedscenes) | &nbsp; | Classifies an image into one of 365 scene categories using DeepStack. |
| [Get-ImageIndexPath](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-imageindexpath) | &nbsp; | Returns the path to the image database, initializing or rebuilding it if needed. |
| [Get-ImageIndexStats](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-imageindexstats) | getimagedbstats, gids | Retrieves comprehensive statistics and information about the image database. |
| [Get-LMStudioLoadedModelList](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-lmstudioloadedmodellist) | &nbsp; | Retrieves the list of currently loaded models from LM Studio. |
| [Get-LMStudioModelList](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-lmstudiomodellist) | &nbsp; | Retrieves a list of installed LM Studio models. |
| [Get-LMStudioPaths](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-lmstudiopaths) | &nbsp; | Retrieves file paths for LM Studio executables. |
| [Get-LMStudioTextEmbedding](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-lmstudiotextembedding) | embed-text, Get-TextEmbedding | Gets text embeddings from LM Studio model. |
| [Get-LMStudioWindow](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-lmstudiowindow) | lmstudiowindow, setlmstudiowindow | Gets a window helper for the LM Studio application. |
| [Get-MediaFileAudioTranscription](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-mediafileaudiotranscription) | transcribefile | Transcribes an audio or video file to text. |
| [Get-NumberOfCpuCores](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-numberofcpucores) | &nbsp; | Calculates and returns the total number of logical CPU cores in the system. |
| [Get-RegisteredFaces](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-registeredfaces) | &nbsp; | Retrieves a list of all registered face identifiers from DeepStack. |
| [Get-ScriptExecutionErrorFixPrompt](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-scriptexecutionerrorfixprompt) | getfixprompt | Captures error messages from various streams and uses LLM to suggest fixes. |
| [Get-SimularMovieTitles](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-simularmovietitles) | &nbsp; | Finds similar movie titles based on common properties. |
| [Get-TextTranslation](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-texttranslation) | translate | Translates text to another language using AI. |
| [Get-VectorSimilarity](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-vectorsimilarity) | &nbsp; | &nbsp; |
| [Initialize-LMStudioModel](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#initialize-lmstudiomodel) | initlmstudio | Initializes and loads an AI model in LM Studio. |
| [Install-LMStudioApplication](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#install-lmstudioapplication) | &nbsp; | Installs LM Studio application using WinGet package manager. |
| [Invoke-AIPowershellCommand](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-aipowershellcommand) | hint | Converts AI command suggestions to JSON format for processing. |
| [Invoke-CommandFromToolCall](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-commandfromtoolcall) | &nbsp; | Executes a tool call function with validation and parameter filtering. |
| [Invoke-ImageEnhancement](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-imageenhancement) | enhanceimage | Enhances an image by enlarging it 4X while improving quality using DeepStack. |
| [Invoke-ImageFacesUpdate](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-imagefacesupdate) | imagepeopledetection | Updates face recognition metadata for image files in a specified directory. |
| [Invoke-ImageKeywordUpdate](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-imagekeywordupdate) | imagekeywordgeneration | Updates image metadata with AI-generated descriptions and keywords. |
| [Invoke-ImageMetadataUpdate](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-imagemetadataupdate) | imagepropdetection | Updates EXIF metadata for images in a directory. |
| [Invoke-ImageObjectsUpdate](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-imageobjectsupdate) | imageobjectdetection | Updates object detection metadata for image files in a specified directory. |
| [Invoke-ImageScenesUpdate](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-imagescenesupdate) | imagescenedetection | Updates scene classification metadata for image files in a specified directory. |
| [Invoke-LLMBooleanEvaluation](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-llmbooleanevaluation) | equalstrue | Evaluates a statement using AI to determine if it's true or false. |
| [Invoke-LLMQuery](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-llmquery) | Invoke-LMStudioQuery, llm, qllm, qlms | &nbsp; |
| [Invoke-LLMStringListEvaluation](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-llmstringlistevaluation) | getlist, getstring | &nbsp; |
| [Invoke-LLMTextTransformation](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-llmtexttransformation) | spellcheck | Transforms text using AI-powered processing. |
| [Invoke-QueryImageContent](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-queryimagecontent) | Query-Image | Analyzes image content using AI vision capabilities through the LM-Studio API. |
| [Invoke-WinMerge](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-winmerge) | &nbsp; | Launches WinMerge to compare two files side by side. |
| [New-LLMAudioChat](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#new-llmaudiochat) | llmaudiochat | Creates an interactive audio chat session with an LLM model. |
| [New-LLMTextChat](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#new-llmtextchat) | llmchat | Starts an interactive text chat session with AI capabilities. |
| [Register-AllFaces](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#register-allfaces) | UpdateFaces | Updates all face recognition profiles from image files in the faces directory. |
| [Register-Face](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#register-face) | &nbsp; | Registers a new face with the DeepStack face recognition API. |
| [Remove-ImageDirectories](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#remove-imagedirectories) | removeimgdir | Removes directories from the configured image directories for GenXdev.AI operations. |
| [Remove-ImageMetaData](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#remove-imagemetadata) | removeimagedata | Removes image metadata files from image directories. |
| [Save-FoundImageFaces](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#save-foundimagefaces) | saveimagefaces | Saves cropped face images from indexed image search results. |
| [Save-FoundImageObjects](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#save-foundimageobjects) | saveimageObjects | Saves cropped object images from indexed image search results to files. |
| [Save-Transcriptions](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#save-transcriptions) | &nbsp; | Generates subtitle files for audio and video files using OpenAI Whisper. |
| [Set-AIImageCollection](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#set-aiimagecollection) | &nbsp; | &nbsp; |
| [Set-AIKnownFacesRootpath](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#set-aiknownfacesrootpath) | &nbsp; | Sets the directory for face image files used in GenXdev.AI operations. |
| [Set-AILLMSettings](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#set-aillmsettings) | &nbsp; | Sets the LLM settings for AI operations in GenXdev.AI. |
| [Set-AIMetaLanguage](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#set-aimetalanguage) | &nbsp; | &nbsp; |
| [Set-GenXdevAICommandNotFoundAction](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#set-genxdevaicommandnotfoundaction) | &nbsp; | Sets up custom command not found handling with AI assistance. |
| [Set-ImageIndexPath](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#set-imageindexpath) | &nbsp; | Sets the default database file path for image operations in GenXdev.AI. |
| [Set-WindowsWallpaperEx](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#set-windowswallpaperex) | nextwallpaper | Sets a random wallpaper from a specified directory or search criteria. |
| [Show-FoundImagesInBrowser](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#show-foundimagesinbrowser) | showfoundimages | Displays image search results in a masonry layout web gallery. |
| [Show-GenXdevScriptErrorFixInIde](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#show-genxdevscripterrorfixinide) | letsfixthis | Executes a script block and analyzes errors using AI to generate fixes in IDE. |
| [Start-AudioTranscription](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#start-audiotranscription) | recordandtranscribe, transcribe | &nbsp; |
| [Start-GenXdevMCPServer](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#start-genxdevmcpserver) | &nbsp; | Starts the GenXdev MCP server that exposes PowerShell cmdlets as tools. |
| [Start-LMStudioApplication](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#start-lmstudioapplication) | &nbsp; | Starts the LM Studio application if it's not already running. |
| [Test-DeepLinkImageFile](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#test-deeplinkimagefile) | &nbsp; | Tests if the specified file path is a valid image file with a supported format. |
| [Test-LMStudioInstallation](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#test-lmstudioinstallation) | &nbsp; | Tests if LMStudio is installed and accessible on the system. |
| [Test-LMStudioProcess](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#test-lmstudioprocess) | &nbsp; | Tests if LM Studio process is running and configures its window state. |
| [Unregister-AllFaces](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#unregister-allfaces) | &nbsp; | Removes all registered faces from the DeepStack face recognition system. |
| [Unregister-Face](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#unregister-face) | &nbsp; | Deletes a registered face by its identifier from DeepStack. |
| [Update-AllImageMetaData](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#update-allimagemetadata) | updateallimages | &nbsp; |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.AI/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.AI.LMStudio

**A Windows PowerShell module for local AI related operations**

### Cmdlet Index

| Command | Aliases | Description |
| --- | --- | --- |
| [Add-EmoticonsToText](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#add-emoticonstotext) | emojify | Enhances text by adding contextually appropriate emoticons using AI. |
| [Add-GenXdevMCPServerToLMStudio](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#add-genxdevmcpservertolmstudio) | &nbsp; | Adds the GenXdev MCP server to LM Studio using a deeplink configuration. |
| [Add-ImageDirectories](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#add-imagedirectories) | addimgdir | Adds directories to the configured image directories for GenXdev.AI operations. |
| [Approve-NewTextFileContent](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#approve-newtextfilecontent) | &nbsp; | Interactive file content comparison and approval using WinMerge. |
| [Compare-ImageFaces](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#compare-imagefaces) | comparefaces | Processes the face match result from DeepStack API. |
| [Convert-DotNetTypeToLLMType](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#convert-dotnettypetollmtype) | &nbsp; | Converts .NET type names to LLM (Language Model) type names. |
| [ConvertFrom-CorporateSpeak](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#convertfrom-corporatespeak) | uncorporatize | Converts polite, professional corporate speak into direct, clear language using AI. |
| [ConvertFrom-DiplomaticSpeak](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#convertfrom-diplomaticspeak) | undiplomatize | &nbsp; |
| [ConvertTo-CorporateSpeak](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#convertto-corporatespeak) | corporatize | Converts direct or blunt text into polite, professional corporate speak using AI. |
| [ConvertTo-DiplomaticSpeak](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#convertto-diplomaticspeak) | diplomatize | Converts direct or blunt text into polite, tactful diplomatic language. |
| [ConvertTo-LMStudioFunctionDefinition](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#convertto-lmstudiofunctiondefinition) | &nbsp; | Converts PowerShell functions to LMStudio function definitions. |
| [EnsureDeepStack](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#ensuredeepstack) | &nbsp; | Ensures DeepStack face recognition service is installed and running. |
| [EnsureGithubCLIInstalled](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#ensuregithubcliinstalled) | &nbsp; | Ensures GitHub CLI is properly installed and configured on the system. |
| [EnsureLMStudio](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#ensurelmstudio) | &nbsp; | Ensures LM Studio is properly initialized with the specified model. |
| [EnsurePaintNet](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#ensurepaintnet) | &nbsp; | Ensures Paint.NET is properly installed and accessible on the system. |
| [EnsureWinMergeInstalled](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#ensurewinmergeinstalled) | &nbsp; | Ensures WinMerge is installed and available for file comparison operations. |
| [Export-ImageIndex](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#export-imageindex) | indeximages | Initializes and populates the SQLite database by discovering images directly. |
| [Find-Image](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#find-image) | findimages, li | &nbsp; |
| [Find-IndexedImage](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#find-indexedimage) | findindexedimages, lii | Searches for images using an optimized SQLite database with fast indexed lookups. |
| [GenerateMasonryLayoutHtml](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#generatemasonrylayouthtml) | &nbsp; | Generates a responsive masonry layout HTML gallery from image data. |
| [Get-AIDefaultLLMSettings](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-aidefaultllmsettings) | &nbsp; | Gets all available default LLM settings configurations for AI operations in GenXdev.AI. |
| [Get-AIImageCollection](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-aiimagecollection) | getimgdirs | Gets the configured directories for image files used in GenXdev.AI operations. |
| [Get-AIKnownFacesRootpath](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-aiknownfacesrootpath) | &nbsp; | &nbsp; |
| [Get-AILLMSettings](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-aillmsettings) | &nbsp; | Gets the LLM settings for AI operations in GenXdev.AI. |
| [Get-AIMetaLanguage](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-aimetalanguage) | getimgmetalang | Gets the configured default language for image metadata operations. |
| [Get-CpuCore](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-cpucore) | &nbsp; | Calculates and returns the total number of logical CPU cores in the system. |
| [Get-Fallacy](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-fallacy) | dispicetext | Analyzes text to identify logical fallacies using AI-powered detection. |
| [Get-HasCapableGpu](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-hascapablegpu) | &nbsp; | Determines if a CUDA-capable GPU with sufficient memory is present. |
| [Get-ImageDetectedFaces](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-imagedetectedfaces) | &nbsp; | &nbsp; |
| [Get-ImageDetectedObjects](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-imagedetectedobjects) | &nbsp; | Detects and classifies objects in an uploaded image using DeepStack. |
| [Get-ImageDetectedScenes](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-imagedetectedscenes) | &nbsp; | Classifies an image into one of 365 scene categories using DeepStack. |
| [Get-ImageIndexPath](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-imageindexpath) | &nbsp; | Returns the path to the image database, initializing or rebuilding it if needed. |
| [Get-ImageIndexStats](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-imageindexstats) | getimagedbstats, gids | Retrieves comprehensive statistics and information about the image database. |
| [Get-LMStudioLoadedModelList](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-lmstudioloadedmodellist) | &nbsp; | Retrieves the list of currently loaded models from LM Studio. |
| [Get-LMStudioModelList](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-lmstudiomodellist) | &nbsp; | Retrieves a list of installed LM Studio models. |
| [Get-LMStudioPaths](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-lmstudiopaths) | &nbsp; | Retrieves file paths for LM Studio executables. |
| [Get-LMStudioTextEmbedding](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-lmstudiotextembedding) | embed-text, Get-TextEmbedding | Gets text embeddings from LM Studio model. |
| [Get-LMStudioWindow](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-lmstudiowindow) | lmstudiowindow, setlmstudiowindow | Gets a window helper for the LM Studio application. |
| [Get-MediaFileAudioTranscription](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-mediafileaudiotranscription) | transcribefile | Transcribes an audio or video file to text. |
| [Get-NumberOfCpuCores](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-numberofcpucores) | &nbsp; | Calculates and returns the total number of logical CPU cores in the system. |
| [Get-RegisteredFaces](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-registeredfaces) | &nbsp; | Retrieves a list of all registered face identifiers from DeepStack. |
| [Get-ScriptExecutionErrorFixPrompt](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-scriptexecutionerrorfixprompt) | getfixprompt | Captures error messages from various streams and uses LLM to suggest fixes. |
| [Get-SimularMovieTitles](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-simularmovietitles) | &nbsp; | Finds similar movie titles based on common properties. |
| [Get-TextTranslation](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-texttranslation) | translate | Translates text to another language using AI. |
| [Get-VectorSimilarity](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-vectorsimilarity) | &nbsp; | &nbsp; |
| [Initialize-LMStudioModel](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#initialize-lmstudiomodel) | initlmstudio | Initializes and loads an AI model in LM Studio. |
| [Install-LMStudioApplication](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#install-lmstudioapplication) | &nbsp; | Installs LM Studio application using WinGet package manager. |
| [Invoke-AIPowershellCommand](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-aipowershellcommand) | hint | Converts AI command suggestions to JSON format for processing. |
| [Invoke-CommandFromToolCall](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-commandfromtoolcall) | &nbsp; | Executes a tool call function with validation and parameter filtering. |
| [Invoke-ImageEnhancement](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-imageenhancement) | enhanceimage | Enhances an image by enlarging it 4X while improving quality using DeepStack. |
| [Invoke-ImageFacesUpdate](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-imagefacesupdate) | imagepeopledetection | Updates face recognition metadata for image files in a specified directory. |
| [Invoke-ImageKeywordUpdate](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-imagekeywordupdate) | imagekeywordgeneration | Updates image metadata with AI-generated descriptions and keywords. |
| [Invoke-ImageMetadataUpdate](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-imagemetadataupdate) | imagepropdetection | Updates EXIF metadata for images in a directory. |
| [Invoke-ImageObjectsUpdate](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-imageobjectsupdate) | imageobjectdetection | Updates object detection metadata for image files in a specified directory. |
| [Invoke-ImageScenesUpdate](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-imagescenesupdate) | imagescenedetection | Updates scene classification metadata for image files in a specified directory. |
| [Invoke-LLMBooleanEvaluation](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-llmbooleanevaluation) | equalstrue | Evaluates a statement using AI to determine if it's true or false. |
| [Invoke-LLMQuery](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-llmquery) | Invoke-LMStudioQuery, llm, qllm, qlms | &nbsp; |
| [Invoke-LLMStringListEvaluation](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-llmstringlistevaluation) | getlist, getstring | &nbsp; |
| [Invoke-LLMTextTransformation](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-llmtexttransformation) | spellcheck | Transforms text using AI-powered processing. |
| [Invoke-QueryImageContent](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-queryimagecontent) | Query-Image | Analyzes image content using AI vision capabilities through the LM-Studio API. |
| [Invoke-WinMerge](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-winmerge) | &nbsp; | Launches WinMerge to compare two files side by side. |
| [New-LLMAudioChat](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#new-llmaudiochat) | llmaudiochat | Creates an interactive audio chat session with an LLM model. |
| [New-LLMTextChat](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#new-llmtextchat) | llmchat | Starts an interactive text chat session with AI capabilities. |
| [Register-AllFaces](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#register-allfaces) | UpdateFaces | Updates all face recognition profiles from image files in the faces directory. |
| [Register-Face](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#register-face) | &nbsp; | Registers a new face with the DeepStack face recognition API. |
| [Remove-ImageDirectories](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#remove-imagedirectories) | removeimgdir | Removes directories from the configured image directories for GenXdev.AI operations. |
| [Remove-ImageMetaData](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#remove-imagemetadata) | removeimagedata | Removes image metadata files from image directories. |
| [Save-FoundImageFaces](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#save-foundimagefaces) | saveimagefaces | Saves cropped face images from indexed image search results. |
| [Save-FoundImageObjects](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#save-foundimageobjects) | saveimageObjects | Saves cropped object images from indexed image search results to files. |
| [Save-Transcriptions](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#save-transcriptions) | &nbsp; | Generates subtitle files for audio and video files using OpenAI Whisper. |
| [Set-AIImageCollection](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#set-aiimagecollection) | &nbsp; | &nbsp; |
| [Set-AIKnownFacesRootpath](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#set-aiknownfacesrootpath) | &nbsp; | Sets the directory for face image files used in GenXdev.AI operations. |
| [Set-AILLMSettings](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#set-aillmsettings) | &nbsp; | Sets the LLM settings for AI operations in GenXdev.AI. |
| [Set-AIMetaLanguage](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#set-aimetalanguage) | &nbsp; | &nbsp; |
| [Set-GenXdevAICommandNotFoundAction](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#set-genxdevaicommandnotfoundaction) | &nbsp; | Sets up custom command not found handling with AI assistance. |
| [Set-ImageIndexPath](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#set-imageindexpath) | &nbsp; | Sets the default database file path for image operations in GenXdev.AI. |
| [Set-WindowsWallpaperEx](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#set-windowswallpaperex) | nextwallpaper | Sets a random wallpaper from a specified directory or search criteria. |
| [Show-FoundImagesInBrowser](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#show-foundimagesinbrowser) | showfoundimages | Displays image search results in a masonry layout web gallery. |
| [Show-GenXdevScriptErrorFixInIde](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#show-genxdevscripterrorfixinide) | letsfixthis | Executes a script block and analyzes errors using AI to generate fixes in IDE. |
| [Start-AudioTranscription](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#start-audiotranscription) | recordandtranscribe, transcribe | &nbsp; |
| [Start-GenXdevMCPServer](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#start-genxdevmcpserver) | &nbsp; | Starts the GenXdev MCP server that exposes PowerShell cmdlets as tools. |
| [Start-LMStudioApplication](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#start-lmstudioapplication) | &nbsp; | Starts the LM Studio application if it's not already running. |
| [Test-DeepLinkImageFile](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#test-deeplinkimagefile) | &nbsp; | Tests if the specified file path is a valid image file with a supported format. |
| [Test-LMStudioInstallation](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#test-lmstudioinstallation) | &nbsp; | Tests if LMStudio is installed and accessible on the system. |
| [Test-LMStudioProcess](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#test-lmstudioprocess) | &nbsp; | Tests if LM Studio process is running and configures its window state. |
| [Unregister-AllFaces](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#unregister-allfaces) | &nbsp; | Removes all registered faces from the DeepStack face recognition system. |
| [Unregister-Face](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#unregister-face) | &nbsp; | Deletes a registered face by its identifier from DeepStack. |
| [Update-AllImageMetaData](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#update-allimagemetadata) | updateallimages | &nbsp; |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.AI/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.AI.Queries

**A Windows PowerShell module for local AI related operations**

### Cmdlet Index

| Command | Aliases | Description |
| --- | --- | --- |
| [Add-EmoticonsToText](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#add-emoticonstotext) | emojify | Enhances text by adding contextually appropriate emoticons using AI. |
| [Add-GenXdevMCPServerToLMStudio](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#add-genxdevmcpservertolmstudio) | &nbsp; | Adds the GenXdev MCP server to LM Studio using a deeplink configuration. |
| [Add-ImageDirectories](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#add-imagedirectories) | addimgdir | Adds directories to the configured image directories for GenXdev.AI operations. |
| [Approve-NewTextFileContent](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#approve-newtextfilecontent) | &nbsp; | Interactive file content comparison and approval using WinMerge. |
| [Compare-ImageFaces](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#compare-imagefaces) | comparefaces | Processes the face match result from DeepStack API. |
| [Convert-DotNetTypeToLLMType](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#convert-dotnettypetollmtype) | &nbsp; | Converts .NET type names to LLM (Language Model) type names. |
| [ConvertFrom-CorporateSpeak](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#convertfrom-corporatespeak) | uncorporatize | Converts polite, professional corporate speak into direct, clear language using AI. |
| [ConvertFrom-DiplomaticSpeak](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#convertfrom-diplomaticspeak) | undiplomatize | &nbsp; |
| [ConvertTo-CorporateSpeak](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#convertto-corporatespeak) | corporatize | Converts direct or blunt text into polite, professional corporate speak using AI. |
| [ConvertTo-DiplomaticSpeak](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#convertto-diplomaticspeak) | diplomatize | Converts direct or blunt text into polite, tactful diplomatic language. |
| [ConvertTo-LMStudioFunctionDefinition](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#convertto-lmstudiofunctiondefinition) | &nbsp; | Converts PowerShell functions to LMStudio function definitions. |
| [EnsureDeepStack](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#ensuredeepstack) | &nbsp; | Ensures DeepStack face recognition service is installed and running. |
| [EnsureGithubCLIInstalled](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#ensuregithubcliinstalled) | &nbsp; | Ensures GitHub CLI is properly installed and configured on the system. |
| [EnsureLMStudio](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#ensurelmstudio) | &nbsp; | Ensures LM Studio is properly initialized with the specified model. |
| [EnsurePaintNet](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#ensurepaintnet) | &nbsp; | Ensures Paint.NET is properly installed and accessible on the system. |
| [EnsureWinMergeInstalled](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#ensurewinmergeinstalled) | &nbsp; | Ensures WinMerge is installed and available for file comparison operations. |
| [Export-ImageIndex](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#export-imageindex) | indeximages | Initializes and populates the SQLite database by discovering images directly. |
| [Find-Image](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#find-image) | findimages, li | &nbsp; |
| [Find-IndexedImage](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#find-indexedimage) | findindexedimages, lii | Searches for images using an optimized SQLite database with fast indexed lookups. |
| [GenerateMasonryLayoutHtml](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#generatemasonrylayouthtml) | &nbsp; | Generates a responsive masonry layout HTML gallery from image data. |
| [Get-AIDefaultLLMSettings](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-aidefaultllmsettings) | &nbsp; | Gets all available default LLM settings configurations for AI operations in GenXdev.AI. |
| [Get-AIImageCollection](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-aiimagecollection) | getimgdirs | Gets the configured directories for image files used in GenXdev.AI operations. |
| [Get-AIKnownFacesRootpath](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-aiknownfacesrootpath) | &nbsp; | &nbsp; |
| [Get-AILLMSettings](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-aillmsettings) | &nbsp; | Gets the LLM settings for AI operations in GenXdev.AI. |
| [Get-AIMetaLanguage](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-aimetalanguage) | getimgmetalang | Gets the configured default language for image metadata operations. |
| [Get-CpuCore](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-cpucore) | &nbsp; | Calculates and returns the total number of logical CPU cores in the system. |
| [Get-Fallacy](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-fallacy) | dispicetext | Analyzes text to identify logical fallacies using AI-powered detection. |
| [Get-HasCapableGpu](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-hascapablegpu) | &nbsp; | Determines if a CUDA-capable GPU with sufficient memory is present. |
| [Get-ImageDetectedFaces](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-imagedetectedfaces) | &nbsp; | &nbsp; |
| [Get-ImageDetectedObjects](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-imagedetectedobjects) | &nbsp; | Detects and classifies objects in an uploaded image using DeepStack. |
| [Get-ImageDetectedScenes](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-imagedetectedscenes) | &nbsp; | Classifies an image into one of 365 scene categories using DeepStack. |
| [Get-ImageIndexPath](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-imageindexpath) | &nbsp; | Returns the path to the image database, initializing or rebuilding it if needed. |
| [Get-ImageIndexStats](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-imageindexstats) | getimagedbstats, gids | Retrieves comprehensive statistics and information about the image database. |
| [Get-LMStudioLoadedModelList](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-lmstudioloadedmodellist) | &nbsp; | Retrieves the list of currently loaded models from LM Studio. |
| [Get-LMStudioModelList](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-lmstudiomodellist) | &nbsp; | Retrieves a list of installed LM Studio models. |
| [Get-LMStudioPaths](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-lmstudiopaths) | &nbsp; | Retrieves file paths for LM Studio executables. |
| [Get-LMStudioTextEmbedding](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-lmstudiotextembedding) | embed-text, Get-TextEmbedding | Gets text embeddings from LM Studio model. |
| [Get-LMStudioWindow](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-lmstudiowindow) | lmstudiowindow, setlmstudiowindow | Gets a window helper for the LM Studio application. |
| [Get-MediaFileAudioTranscription](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-mediafileaudiotranscription) | transcribefile | Transcribes an audio or video file to text. |
| [Get-NumberOfCpuCores](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-numberofcpucores) | &nbsp; | Calculates and returns the total number of logical CPU cores in the system. |
| [Get-RegisteredFaces](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-registeredfaces) | &nbsp; | Retrieves a list of all registered face identifiers from DeepStack. |
| [Get-ScriptExecutionErrorFixPrompt](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-scriptexecutionerrorfixprompt) | getfixprompt | Captures error messages from various streams and uses LLM to suggest fixes. |
| [Get-SimularMovieTitles](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-simularmovietitles) | &nbsp; | Finds similar movie titles based on common properties. |
| [Get-TextTranslation](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-texttranslation) | translate | Translates text to another language using AI. |
| [Get-VectorSimilarity](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#get-vectorsimilarity) | &nbsp; | &nbsp; |
| [Initialize-LMStudioModel](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#initialize-lmstudiomodel) | initlmstudio | Initializes and loads an AI model in LM Studio. |
| [Install-LMStudioApplication](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#install-lmstudioapplication) | &nbsp; | Installs LM Studio application using WinGet package manager. |
| [Invoke-AIPowershellCommand](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-aipowershellcommand) | hint | Converts AI command suggestions to JSON format for processing. |
| [Invoke-CommandFromToolCall](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-commandfromtoolcall) | &nbsp; | Executes a tool call function with validation and parameter filtering. |
| [Invoke-ImageEnhancement](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-imageenhancement) | enhanceimage | Enhances an image by enlarging it 4X while improving quality using DeepStack. |
| [Invoke-ImageFacesUpdate](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-imagefacesupdate) | imagepeopledetection | Updates face recognition metadata for image files in a specified directory. |
| [Invoke-ImageKeywordUpdate](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-imagekeywordupdate) | imagekeywordgeneration | Updates image metadata with AI-generated descriptions and keywords. |
| [Invoke-ImageMetadataUpdate](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-imagemetadataupdate) | imagepropdetection | Updates EXIF metadata for images in a directory. |
| [Invoke-ImageObjectsUpdate](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-imageobjectsupdate) | imageobjectdetection | Updates object detection metadata for image files in a specified directory. |
| [Invoke-ImageScenesUpdate](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-imagescenesupdate) | imagescenedetection | Updates scene classification metadata for image files in a specified directory. |
| [Invoke-LLMBooleanEvaluation](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-llmbooleanevaluation) | equalstrue | Evaluates a statement using AI to determine if it's true or false. |
| [Invoke-LLMQuery](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-llmquery) | Invoke-LMStudioQuery, llm, qllm, qlms | &nbsp; |
| [Invoke-LLMStringListEvaluation](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-llmstringlistevaluation) | getlist, getstring | &nbsp; |
| [Invoke-LLMTextTransformation](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-llmtexttransformation) | spellcheck | Transforms text using AI-powered processing. |
| [Invoke-QueryImageContent](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-queryimagecontent) | Query-Image | Analyzes image content using AI vision capabilities through the LM-Studio API. |
| [Invoke-WinMerge](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#invoke-winmerge) | &nbsp; | Launches WinMerge to compare two files side by side. |
| [New-LLMAudioChat](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#new-llmaudiochat) | llmaudiochat | Creates an interactive audio chat session with an LLM model. |
| [New-LLMTextChat](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#new-llmtextchat) | llmchat | Starts an interactive text chat session with AI capabilities. |
| [Register-AllFaces](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#register-allfaces) | UpdateFaces | Updates all face recognition profiles from image files in the faces directory. |
| [Register-Face](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#register-face) | &nbsp; | Registers a new face with the DeepStack face recognition API. |
| [Remove-ImageDirectories](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#remove-imagedirectories) | removeimgdir | Removes directories from the configured image directories for GenXdev.AI operations. |
| [Remove-ImageMetaData](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#remove-imagemetadata) | removeimagedata | Removes image metadata files from image directories. |
| [Save-FoundImageFaces](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#save-foundimagefaces) | saveimagefaces | Saves cropped face images from indexed image search results. |
| [Save-FoundImageObjects](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#save-foundimageobjects) | saveimageObjects | Saves cropped object images from indexed image search results to files. |
| [Save-Transcriptions](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#save-transcriptions) | &nbsp; | Generates subtitle files for audio and video files using OpenAI Whisper. |
| [Set-AIImageCollection](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#set-aiimagecollection) | &nbsp; | &nbsp; |
| [Set-AIKnownFacesRootpath](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#set-aiknownfacesrootpath) | &nbsp; | Sets the directory for face image files used in GenXdev.AI operations. |
| [Set-AILLMSettings](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#set-aillmsettings) | &nbsp; | Sets the LLM settings for AI operations in GenXdev.AI. |
| [Set-AIMetaLanguage](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#set-aimetalanguage) | &nbsp; | &nbsp; |
| [Set-GenXdevAICommandNotFoundAction](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#set-genxdevaicommandnotfoundaction) | &nbsp; | Sets up custom command not found handling with AI assistance. |
| [Set-ImageIndexPath](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#set-imageindexpath) | &nbsp; | Sets the default database file path for image operations in GenXdev.AI. |
| [Set-WindowsWallpaperEx](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#set-windowswallpaperex) | nextwallpaper | Sets a random wallpaper from a specified directory or search criteria. |
| [Show-FoundImagesInBrowser](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#show-foundimagesinbrowser) | showfoundimages | Displays image search results in a masonry layout web gallery. |
| [Show-GenXdevScriptErrorFixInIde](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#show-genxdevscripterrorfixinide) | letsfixthis | Executes a script block and analyzes errors using AI to generate fixes in IDE. |
| [Start-AudioTranscription](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#start-audiotranscription) | recordandtranscribe, transcribe | &nbsp; |
| [Start-GenXdevMCPServer](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#start-genxdevmcpserver) | &nbsp; | Starts the GenXdev MCP server that exposes PowerShell cmdlets as tools. |
| [Start-LMStudioApplication](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#start-lmstudioapplication) | &nbsp; | Starts the LM Studio application if it's not already running. |
| [Test-DeepLinkImageFile](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#test-deeplinkimagefile) | &nbsp; | Tests if the specified file path is a valid image file with a supported format. |
| [Test-LMStudioInstallation](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#test-lmstudioinstallation) | &nbsp; | Tests if LMStudio is installed and accessible on the system. |
| [Test-LMStudioProcess](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#test-lmstudioprocess) | &nbsp; | Tests if LM Studio process is running and configures its window state. |
| [Unregister-AllFaces](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#unregister-allfaces) | &nbsp; | Removes all registered faces from the DeepStack face recognition system. |
| [Unregister-Face](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#unregister-face) | &nbsp; | Deletes a registered face by its identifier from DeepStack. |
| [Update-AllImageMetaData](https://github.com/genXdev/GenXdev.AI/blob/main/README.md#update-allimagemetadata) | updateallimages | &nbsp; |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.AI/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Coding

**A Windows PowerShell module that helps being more productive with coding tasks.**

### Cmdlet Index

| Command | Aliases | Description |
| --- | --- | --- |
| [Add-FeatureLineToREADME](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#add-featurelinetoreadme) | feature | Adds a feature line to the README file with a timestamp. |
| [Add-IdeaLineToREADME](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#add-idealinetoreadme) | idea | Adds an idea item to the README.md file. |
| [Add-IssueLineToREADME](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#add-issuelinetoreadme) | issue | Adds an issue item to the README.md file. |
| [Add-LineToREADME](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#add-linetoreadme) | &nbsp; | Adds a line to a README.md markdown file in a specified section. |
| [Add-MissingGenXdevUnitTests](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#add-missinggenxdevunittests) | &nbsp; | &nbsp; |
| [Add-ReleaseNoteLineToREADME](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#add-releasenotelinetoreadme) | ReleaseNote | Adds a ReleaseNote line to the README file with a timestamp. |
| [Add-TodoLineToREADME](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#add-todolinetoreadme) | todo | Adds a todo item to the README.md file. |
| [Assert-GenXdevCmdlet](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#assert-genxdevcmdlet) | improvecmdlet | Improves GenXdev cmdlet documentation and implementation through AI assistance. |
| [Assert-GenXdevCmdletTests](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#assert-genxdevcmdlettests) | improvecmdlettests | Asserts and improves unit-tests of a specified GenXdev cmdlet. |
| [Assert-GenXdevDependencyUsage](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#assert-genxdevdependencyusage) | checkgenxdevdependencies | &nbsp; |
| [Assert-GenXdevTest](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#assert-genxdevtest) | Assert-GenXdevUnitTest, rungenxdevtests, testcmdlet | &nbsp; |
| [Assert-ModuleDefinition](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#assert-moduledefinition) | &nbsp; | Assists in refactoring PowerShell source code files using AI assistance. |
| [Assert-RefactorFile](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#assert-refactorfile) | &nbsp; | &nbsp; |
| [Clear-GenXdevModules](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#clear-genxdevmodules) | cleangenxdev | Cleans build artifacts from GenXdev PowerShell modules. |
| [Complete-GenXDevREADME](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#complete-genxdevreadme) | &nbsp; | Completes the README file for specified GenXDev modules by adding documentation. |
| [EnsureCopilotKeyboardShortCut](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#ensurecopilotkeyboardshortcut) | &nbsp; | Configures the GitHub Copilot Chat keyboard shortcuts in Visual Studio Code. |
| [EnsureDefaultGenXdevRefactors](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#ensuredefaultgenxdevrefactors) | &nbsp; | &nbsp; |
| [EnsureVSCodeInstallation](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#ensurevscodeinstallation) | &nbsp; | Installs and configures Visual Studio Code with recommended extensions. |
| [Features](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#features) | &nbsp; | Displays features from a README.md file. |
| [Get-GenXdevCmdletUsageAnalysis](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#get-genxdevcmdletusageanalysis) | &nbsp; | Analyzes GenXdev cmdlet usage patterns to identify most frequently called functions. |
| [Get-GenXDevModule](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#get-genxdevmodule) | &nbsp; | Retrieves all GenXDev modules from a specified path. |
| [Get-GenXDevModuleInfo](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#get-genxdevmoduleinfo) | &nbsp; | Retrieves detailed information about GenXdev PowerShell modules. |
| [Get-GenXDevNewModulesInOrderOfDependency](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#get-genxdevnewmodulesinorderofdependency) | &nbsp; | Retrieves GenXDev modules in dependency order. |
| [Get-GitChangedFiles](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#get-gitchangedfiles) | Get-GitChangedFile, gitchanged | Get the list of changed files in a Git repository. |
| [Get-ModuleHelpMarkdown](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#get-modulehelpmarkdown) | Get-GenXDevModuleHelp | Generates markdown help documentation for specified GenXDev modules. |
| [Get-Refactor](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#get-refactor) | refactor, refactors, Show-RefactorReport | Retrieves refactor definitions from GenXdev preferences based on name patterns. |
| [Get-RefactorReport](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#get-refactorreport) | refactorreport | Generates a detailed report of refactoring operations and their status. |
| [Ideas](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#ideas) | &nbsp; | Displays ideas from a README.md file. |
| [Invoke-GenXdevPSFormatter](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#invoke-genxdevpsformatter) | &nbsp; | Formats PowerShell script files using PSScriptAnalyzer formatting rules. |
| [Invoke-GenXdevScriptAnalyzer](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#invoke-genxdevscriptanalyzer) | &nbsp; | &nbsp; |
| [Issues](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#issues) | &nbsp; | Displays issues from a README.md file. |
| [New-GenXdevCmdlet](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#new-genxdevcmdlet) | newcmd | Creates a new GenXdev PowerShell cmdlet with proper structure and validation. |
| [New-GenXdevModule](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#new-genxdevmodule) | &nbsp; | Creates a new GenXdev PowerShell module with proper structure and configuration. |
| [New-GitCommit](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#new-gitcommit) | commit | Creates and pushes a new git commit with all changes. |
| [New-PullRequestForGenXdevModuleChanges](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#new-pullrequestforgenxdevmodulechanges) | prgenxdevmodule | Creates a pull request for changes made to a GenXdev module. |
| [New-Refactor](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#new-refactor) | newrefactor | Creates a new refactoring set for code transformation tasks. |
| [Open-GenXdevCmdletsContainingClipboardTextInIde](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#open-genxdevcmdletscontainingclipboardtextinide) | vscodesearch | Opens files in IDE that contain clipboard text |
| [Open-SourceFileInIde](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#open-sourcefileinide) | editcode | Opens a source file in the preferred IDE (Visual Studio Code or Visual Studio). |
| [PermanentlyDeleteGitFolders](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#permanentlydeletegitfolders) | &nbsp; | Permanently deletes specified folders from all branches in a Git repository. |
| [ReleaseNotes](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#releasenotes) | &nbsp; | Displays ReleaseNotes from a README.md file. |
| [Remove-Refactor](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#remove-refactor) | &nbsp; | Removes refactor sets from GenXdev preferences system. |
| [Search-GenXdevCmdlet](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#search-genxdevcmdlet) | searchcmdlet | Searches for a GenXdev cmdlet and optionally opens it in an IDE for editing. |
| [Show-GenXdevCmdLetInIde](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#show-genxdevcmdletinide) | editcmdlet | Opens the specified GenXdev cmdlet in Visual Studio Code. |
| [SplitUpPsm1File](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#splituppsm1file) | &nbsp; | Splits a PowerShell module (.psm1) file into individual function files. |
| [Start-NextRefactor](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#start-nextrefactor) | nextrefactor | Continues or restarts a code refactoring session. |
| [Test-RefactorLLMSelection](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#test-refactorllmselection) | &nbsp; | Evaluates source files for refactoring eligibility using LLM analysis. |
| [Todoos](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#todoos) | &nbsp; | Displays todo items from a README.md file. |
| [Update-Refactor](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#update-refactor) | updaterefactor | Updates and manages refactoring sets including file selection and processing. |
| [VSCode](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#vscode) | &nbsp; | Opens one or more files in Visual Studio Code. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Coding.Git

**A Windows PowerShell module that helps being more productive with coding tasks.**

### Cmdlet Index

| Command | Aliases | Description |
| --- | --- | --- |
| [Add-FeatureLineToREADME](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#add-featurelinetoreadme) | feature | Adds a feature line to the README file with a timestamp. |
| [Add-IdeaLineToREADME](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#add-idealinetoreadme) | idea | Adds an idea item to the README.md file. |
| [Add-IssueLineToREADME](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#add-issuelinetoreadme) | issue | Adds an issue item to the README.md file. |
| [Add-LineToREADME](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#add-linetoreadme) | &nbsp; | Adds a line to a README.md markdown file in a specified section. |
| [Add-MissingGenXdevUnitTests](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#add-missinggenxdevunittests) | &nbsp; | &nbsp; |
| [Add-ReleaseNoteLineToREADME](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#add-releasenotelinetoreadme) | ReleaseNote | Adds a ReleaseNote line to the README file with a timestamp. |
| [Add-TodoLineToREADME](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#add-todolinetoreadme) | todo | Adds a todo item to the README.md file. |
| [Assert-GenXdevCmdlet](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#assert-genxdevcmdlet) | improvecmdlet | Improves GenXdev cmdlet documentation and implementation through AI assistance. |
| [Assert-GenXdevCmdletTests](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#assert-genxdevcmdlettests) | improvecmdlettests | Asserts and improves unit-tests of a specified GenXdev cmdlet. |
| [Assert-GenXdevDependencyUsage](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#assert-genxdevdependencyusage) | checkgenxdevdependencies | &nbsp; |
| [Assert-GenXdevTest](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#assert-genxdevtest) | Assert-GenXdevUnitTest, rungenxdevtests, testcmdlet | &nbsp; |
| [Assert-ModuleDefinition](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#assert-moduledefinition) | &nbsp; | Assists in refactoring PowerShell source code files using AI assistance. |
| [Assert-RefactorFile](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#assert-refactorfile) | &nbsp; | &nbsp; |
| [Clear-GenXdevModules](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#clear-genxdevmodules) | cleangenxdev | Cleans build artifacts from GenXdev PowerShell modules. |
| [Complete-GenXDevREADME](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#complete-genxdevreadme) | &nbsp; | Completes the README file for specified GenXDev modules by adding documentation. |
| [EnsureCopilotKeyboardShortCut](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#ensurecopilotkeyboardshortcut) | &nbsp; | Configures the GitHub Copilot Chat keyboard shortcuts in Visual Studio Code. |
| [EnsureDefaultGenXdevRefactors](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#ensuredefaultgenxdevrefactors) | &nbsp; | &nbsp; |
| [EnsureVSCodeInstallation](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#ensurevscodeinstallation) | &nbsp; | Installs and configures Visual Studio Code with recommended extensions. |
| [Features](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#features) | &nbsp; | Displays features from a README.md file. |
| [Get-GenXdevCmdletUsageAnalysis](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#get-genxdevcmdletusageanalysis) | &nbsp; | Analyzes GenXdev cmdlet usage patterns to identify most frequently called functions. |
| [Get-GenXDevModule](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#get-genxdevmodule) | &nbsp; | Retrieves all GenXDev modules from a specified path. |
| [Get-GenXDevModuleInfo](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#get-genxdevmoduleinfo) | &nbsp; | Retrieves detailed information about GenXdev PowerShell modules. |
| [Get-GenXDevNewModulesInOrderOfDependency](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#get-genxdevnewmodulesinorderofdependency) | &nbsp; | Retrieves GenXDev modules in dependency order. |
| [Get-GitChangedFiles](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#get-gitchangedfiles) | Get-GitChangedFile, gitchanged | Get the list of changed files in a Git repository. |
| [Get-ModuleHelpMarkdown](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#get-modulehelpmarkdown) | Get-GenXDevModuleHelp | Generates markdown help documentation for specified GenXDev modules. |
| [Get-Refactor](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#get-refactor) | refactor, refactors, Show-RefactorReport | Retrieves refactor definitions from GenXdev preferences based on name patterns. |
| [Get-RefactorReport](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#get-refactorreport) | refactorreport | Generates a detailed report of refactoring operations and their status. |
| [Ideas](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#ideas) | &nbsp; | Displays ideas from a README.md file. |
| [Invoke-GenXdevPSFormatter](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#invoke-genxdevpsformatter) | &nbsp; | Formats PowerShell script files using PSScriptAnalyzer formatting rules. |
| [Invoke-GenXdevScriptAnalyzer](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#invoke-genxdevscriptanalyzer) | &nbsp; | &nbsp; |
| [Issues](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#issues) | &nbsp; | Displays issues from a README.md file. |
| [New-GenXdevCmdlet](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#new-genxdevcmdlet) | newcmd | Creates a new GenXdev PowerShell cmdlet with proper structure and validation. |
| [New-GenXdevModule](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#new-genxdevmodule) | &nbsp; | Creates a new GenXdev PowerShell module with proper structure and configuration. |
| [New-GitCommit](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#new-gitcommit) | commit | Creates and pushes a new git commit with all changes. |
| [New-PullRequestForGenXdevModuleChanges](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#new-pullrequestforgenxdevmodulechanges) | prgenxdevmodule | Creates a pull request for changes made to a GenXdev module. |
| [New-Refactor](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#new-refactor) | newrefactor | Creates a new refactoring set for code transformation tasks. |
| [Open-GenXdevCmdletsContainingClipboardTextInIde](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#open-genxdevcmdletscontainingclipboardtextinide) | vscodesearch | Opens files in IDE that contain clipboard text |
| [Open-SourceFileInIde](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#open-sourcefileinide) | editcode | Opens a source file in the preferred IDE (Visual Studio Code or Visual Studio). |
| [PermanentlyDeleteGitFolders](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#permanentlydeletegitfolders) | &nbsp; | Permanently deletes specified folders from all branches in a Git repository. |
| [ReleaseNotes](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#releasenotes) | &nbsp; | Displays ReleaseNotes from a README.md file. |
| [Remove-Refactor](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#remove-refactor) | &nbsp; | Removes refactor sets from GenXdev preferences system. |
| [Search-GenXdevCmdlet](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#search-genxdevcmdlet) | searchcmdlet | Searches for a GenXdev cmdlet and optionally opens it in an IDE for editing. |
| [Show-GenXdevCmdLetInIde](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#show-genxdevcmdletinide) | editcmdlet | Opens the specified GenXdev cmdlet in Visual Studio Code. |
| [SplitUpPsm1File](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#splituppsm1file) | &nbsp; | Splits a PowerShell module (.psm1) file into individual function files. |
| [Start-NextRefactor](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#start-nextrefactor) | nextrefactor | Continues or restarts a code refactoring session. |
| [Test-RefactorLLMSelection](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#test-refactorllmselection) | &nbsp; | Evaluates source files for refactoring eligibility using LLM analysis. |
| [Todoos](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#todoos) | &nbsp; | Displays todo items from a README.md file. |
| [Update-Refactor](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#update-refactor) | updaterefactor | Updates and manages refactoring sets including file selection and processing. |
| [VSCode](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#vscode) | &nbsp; | Opens one or more files in Visual Studio Code. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Coding.PowerShell.Modules

**A Windows PowerShell module that helps being more productive with coding tasks.**

### Cmdlet Index

| Command | Aliases | Description |
| --- | --- | --- |
| [Add-FeatureLineToREADME](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#add-featurelinetoreadme) | feature | Adds a feature line to the README file with a timestamp. |
| [Add-IdeaLineToREADME](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#add-idealinetoreadme) | idea | Adds an idea item to the README.md file. |
| [Add-IssueLineToREADME](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#add-issuelinetoreadme) | issue | Adds an issue item to the README.md file. |
| [Add-LineToREADME](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#add-linetoreadme) | &nbsp; | Adds a line to a README.md markdown file in a specified section. |
| [Add-MissingGenXdevUnitTests](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#add-missinggenxdevunittests) | &nbsp; | &nbsp; |
| [Add-ReleaseNoteLineToREADME](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#add-releasenotelinetoreadme) | ReleaseNote | Adds a ReleaseNote line to the README file with a timestamp. |
| [Add-TodoLineToREADME](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#add-todolinetoreadme) | todo | Adds a todo item to the README.md file. |
| [Assert-GenXdevCmdlet](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#assert-genxdevcmdlet) | improvecmdlet | Improves GenXdev cmdlet documentation and implementation through AI assistance. |
| [Assert-GenXdevCmdletTests](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#assert-genxdevcmdlettests) | improvecmdlettests | Asserts and improves unit-tests of a specified GenXdev cmdlet. |
| [Assert-GenXdevDependencyUsage](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#assert-genxdevdependencyusage) | checkgenxdevdependencies | &nbsp; |
| [Assert-GenXdevTest](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#assert-genxdevtest) | Assert-GenXdevUnitTest, rungenxdevtests, testcmdlet | &nbsp; |
| [Assert-ModuleDefinition](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#assert-moduledefinition) | &nbsp; | Assists in refactoring PowerShell source code files using AI assistance. |
| [Assert-RefactorFile](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#assert-refactorfile) | &nbsp; | &nbsp; |
| [Clear-GenXdevModules](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#clear-genxdevmodules) | cleangenxdev | Cleans build artifacts from GenXdev PowerShell modules. |
| [Complete-GenXDevREADME](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#complete-genxdevreadme) | &nbsp; | Completes the README file for specified GenXDev modules by adding documentation. |
| [EnsureCopilotKeyboardShortCut](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#ensurecopilotkeyboardshortcut) | &nbsp; | Configures the GitHub Copilot Chat keyboard shortcuts in Visual Studio Code. |
| [EnsureDefaultGenXdevRefactors](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#ensuredefaultgenxdevrefactors) | &nbsp; | &nbsp; |
| [EnsureVSCodeInstallation](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#ensurevscodeinstallation) | &nbsp; | Installs and configures Visual Studio Code with recommended extensions. |
| [Features](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#features) | &nbsp; | Displays features from a README.md file. |
| [Get-GenXdevCmdletUsageAnalysis](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#get-genxdevcmdletusageanalysis) | &nbsp; | Analyzes GenXdev cmdlet usage patterns to identify most frequently called functions. |
| [Get-GenXDevModule](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#get-genxdevmodule) | &nbsp; | Retrieves all GenXDev modules from a specified path. |
| [Get-GenXDevModuleInfo](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#get-genxdevmoduleinfo) | &nbsp; | Retrieves detailed information about GenXdev PowerShell modules. |
| [Get-GenXDevNewModulesInOrderOfDependency](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#get-genxdevnewmodulesinorderofdependency) | &nbsp; | Retrieves GenXDev modules in dependency order. |
| [Get-GitChangedFiles](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#get-gitchangedfiles) | Get-GitChangedFile, gitchanged | Get the list of changed files in a Git repository. |
| [Get-ModuleHelpMarkdown](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#get-modulehelpmarkdown) | Get-GenXDevModuleHelp | Generates markdown help documentation for specified GenXDev modules. |
| [Get-Refactor](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#get-refactor) | refactor, refactors, Show-RefactorReport | Retrieves refactor definitions from GenXdev preferences based on name patterns. |
| [Get-RefactorReport](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#get-refactorreport) | refactorreport | Generates a detailed report of refactoring operations and their status. |
| [Ideas](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#ideas) | &nbsp; | Displays ideas from a README.md file. |
| [Invoke-GenXdevPSFormatter](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#invoke-genxdevpsformatter) | &nbsp; | Formats PowerShell script files using PSScriptAnalyzer formatting rules. |
| [Invoke-GenXdevScriptAnalyzer](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#invoke-genxdevscriptanalyzer) | &nbsp; | &nbsp; |
| [Issues](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#issues) | &nbsp; | Displays issues from a README.md file. |
| [New-GenXdevCmdlet](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#new-genxdevcmdlet) | newcmd | Creates a new GenXdev PowerShell cmdlet with proper structure and validation. |
| [New-GenXdevModule](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#new-genxdevmodule) | &nbsp; | Creates a new GenXdev PowerShell module with proper structure and configuration. |
| [New-GitCommit](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#new-gitcommit) | commit | Creates and pushes a new git commit with all changes. |
| [New-PullRequestForGenXdevModuleChanges](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#new-pullrequestforgenxdevmodulechanges) | prgenxdevmodule | Creates a pull request for changes made to a GenXdev module. |
| [New-Refactor](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#new-refactor) | newrefactor | Creates a new refactoring set for code transformation tasks. |
| [Open-GenXdevCmdletsContainingClipboardTextInIde](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#open-genxdevcmdletscontainingclipboardtextinide) | vscodesearch | Opens files in IDE that contain clipboard text |
| [Open-SourceFileInIde](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#open-sourcefileinide) | editcode | Opens a source file in the preferred IDE (Visual Studio Code or Visual Studio). |
| [PermanentlyDeleteGitFolders](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#permanentlydeletegitfolders) | &nbsp; | Permanently deletes specified folders from all branches in a Git repository. |
| [ReleaseNotes](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#releasenotes) | &nbsp; | Displays ReleaseNotes from a README.md file. |
| [Remove-Refactor](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#remove-refactor) | &nbsp; | Removes refactor sets from GenXdev preferences system. |
| [Search-GenXdevCmdlet](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#search-genxdevcmdlet) | searchcmdlet | Searches for a GenXdev cmdlet and optionally opens it in an IDE for editing. |
| [Show-GenXdevCmdLetInIde](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#show-genxdevcmdletinide) | editcmdlet | Opens the specified GenXdev cmdlet in Visual Studio Code. |
| [SplitUpPsm1File](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#splituppsm1file) | &nbsp; | Splits a PowerShell module (.psm1) file into individual function files. |
| [Start-NextRefactor](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#start-nextrefactor) | nextrefactor | Continues or restarts a code refactoring session. |
| [Test-RefactorLLMSelection](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#test-refactorllmselection) | &nbsp; | Evaluates source files for refactoring eligibility using LLM analysis. |
| [Todoos](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#todoos) | &nbsp; | Displays todo items from a README.md file. |
| [Update-Refactor](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#update-refactor) | updaterefactor | Updates and manages refactoring sets including file selection and processing. |
| [VSCode](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md#vscode) | &nbsp; | Opens one or more files in Visual Studio Code. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Coding/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Console

**A Windows PowerShell module for enhancing the commandline experience**

### Cmdlet Index

| Command | Aliases | Description |
| --- | --- | --- |
| [Add-SpotifyNewPlaylist](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#add-spotifynewplaylist) | newplaylist | Creates a new Spotify playlist with customizable settings. |
| [Add-SpotifyTracksToLiked](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#add-spotifytrackstoliked) | like | Adds tracks to the user's Spotify liked songs library. |
| [Add-SpotifyTracksToPlaylist](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#add-spotifytrackstoplaylist) | addtoplaylist | Adds tracks to a Spotify playlist. |
| [Connect-SpotifyApiToken](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#connect-spotifyapitoken) | &nbsp; | Authenticates with Spotify API using OAuth flow to obtain an access token. |
| [Enable-Screensaver](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#enable-screensaver) | &nbsp; | Starts the configured Windows screensaver. |
| [Get-IsSpeaking](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#get-isspeaking) | iss | Returns true if the text-to-speech engine is speaking. |
| [Get-SpotifyActiveDevice](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#get-spotifyactivedevice) | &nbsp; | Returns all currently active Spotify devices for the current user. |
| [Get-SpotifyApiToken](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#get-spotifyapitoken) | &nbsp; | Retrieves or generates a valid Spotify API authentication token. |
| [Get-SpotifyCurrentlyPlaying](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#get-spotifycurrentlyplaying) | gcp | Returns information about the currently playing track on Spotify. |
| [Get-SpotifyDevice](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#get-spotifydevice) | Get-SpotifyDevices | Returns all currently available Spotify devices for current user. |
| [Get-SpotifyLikedTrack](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#get-spotifylikedtrack) | liked | Retrieves all tracks saved in the user's Spotify Library. |
| [Get-SpotifyLyrics](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#get-spotifylyrics) | lyrics | Retrieves lyrics for Spotify tracks from Musixmatch.com |
| [Get-SpotifyPlaylistIdsByName](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#get-spotifyplaylistidsbyname) | &nbsp; | Retrieves Spotify playlist IDs by their names. |
| [Get-SpotifyPlaylistTrack](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#get-spotifyplaylisttrack) | getplaylist | Returns all tracks from a Spotify playlist. |
| [Get-SpotifyTrackAudioFeatures](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#get-spotifytrackaudiofeatures) | audiofeatures | Retrieves audio feature information for one or more Spotify tracks. |
| [Get-SpotifyTrackById](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#get-spotifytrackbyid) | gettrack | Retrieves detailed track information from Spotify using a track ID. |
| [Get-SpotifyUserPlaylists](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#get-spotifyuserplaylists) | gupl | Returns a collection of Spotify playlists owned by the current user. |
| [Move-SpotifyLikedTracksToPlaylist](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#move-spotifylikedtrackstoplaylist) | moveliked | Moves all liked tracks from your Spotify library to specified playlist(s) |
| [New-MicrosoftShellTab](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#new-microsoftshelltab) | x | Creates a new Windows Terminal tab running PowerShell. |
| [Now](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#now) | &nbsp; | Returns the current system date and time as a DateTime object. |
| [Open-MediaFile](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#open-mediafile) | findmedia, media, vlcmedia | &nbsp; |
| [Open-VlcMediaPlayer](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#open-vlcmediaplayer) | vlc | Launches and controls VLC Media Player with extensive configuration options. |
| [Open-VlcMediaPlayerLyrics](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#open-vlcmediaplayerlyrics) | vlclyrics | Opens a web browser to search for lyrics of currently playing VLC media. |
| [Remove-SpotifyTracksFromLiked](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#remove-spotifytracksfromliked) | dislike | Removes tracks from the user's Spotify Library (Liked Songs). |
| [Remove-SpotifyTracksFromPlaylist](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#remove-spotifytracksfromplaylist) | removefromplaylist | Removes tracks from a Spotify playlist. |
| [SayDate](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#saydate) | &nbsp; | Speaks the current date using text-to-speech synthesis. |
| [SayTime](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#saytime) | &nbsp; | Announces the current time using text-to-speech. |
| [Search-Spotify](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#search-spotify) | fm, sm | Performs a Spotify search and returns matching items. |
| [Search-SpotifyAndEnqueue](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#search-spotifyandenqueue) | fmq, smq | Searches Spotify and adds the first matching item to the playback queue. |
| [Search-SpotifyAndPlay](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#search-spotifyandplay) | fmp, smp | Performs a Spotify search and plays the first found item. |
| [Set-LocationParent](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-locationparent) | .. | Changes the current location to the parent directory and lists its contents. |
| [Set-LocationParent2](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-locationparent2) | ... | Navigates up two directory levels in the file system hierarchy. |
| [Set-LocationParent3](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-locationparent3) | .... | Navigates up three directory levels in the file system hierarchy. |
| [Set-LocationParent4](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-locationparent4) | ..... | Navigates up four directory levels in the filesystem hierarchy. |
| [Set-LocationParent5](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-locationparent5) | ...... | Navigates up five directory levels in the file system hierarchy. |
| [Set-MonitorPowerOff](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-monitorpoweroff) | poweroff | Turns off power to all connected monitors. |
| [Set-MonitorPowerOn](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-monitorpoweron) | wake-monitor | Turns the monitor power on. |
| [Set-SpotifyActiveDevice](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-spotifyactivedevice) | Set-SpotifyDevice | Sets the active Spotify playback device. |
| [Set-SpotifyApiToken](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-spotifyapitoken) | &nbsp; | Caches a Spotify API token for later use in the local configuration. |
| [Set-SpotifyNext](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-spotifynext) | next, skip | Skips to next track on Spotify. |
| [Set-SpotifyPause](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-spotifypause) | pausemusic, Resume-Music | Pauses Spotify playback |
| [Set-SpotifyPlaylistDetails](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-spotifyplaylistdetails) | spld | Sets the main properties of a Spotify playlist. |
| [Set-SpotifyPlaylistOrder](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-spotifyplaylistorder) | &nbsp; | &nbsp; |
| [Set-SpotifyPrevious](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-spotifyprevious) | prev, previous | Skips to the previous track in Spotify playback. |
| [Set-SpotifyRepeatContext](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-spotifyrepeatcontext) | repeat | Enables playlist repeat mode for Spotify playback. |
| [Set-SpotifyRepeatOff](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-spotifyrepeatoff) | norepeat, repeatoff | Disables Spotify repeat mode for the currently active device. |
| [Set-SpotifyRepeatSong](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-spotifyrepeatsong) | repeatsong | Enables song repeat mode in Spotify. |
| [Set-SpotifyShuffleOff](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-spotifyshuffleoff) | noshuffle, shuffleoff | Disables Spotify song-shuffle mode on the active device. |
| [Set-SpotifyShuffleOn](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-spotifyshuffleon) | shuffle, shuffleon | Enables Spotify song-shuffle mode. |
| [Set-SpotifyStart](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-spotifystart) | play, Start-Music | Starts Spotify playback on the currently active device. |
| [Set-SpotifyStop](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-spotifystop) | stop | Stops Spotify playback on the active device. |
| [Set-VLCPlayerFocused](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-vlcplayerfocused) | fvlc, showvlc, vlcf | Sets focus to the VLC media player window. |
| [Start-TextToSpeech](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#start-texttospeech) | say | Converts text to speech using the Windows Speech API. |
| [Start-VlcMediaPlayerNextInPlaylist](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#start-vlcmediaplayernextinplaylist) | vlcnext | Advances VLC Media Player to the next item in the current playlist. |
| [Start-VlcMediaPlayerPreviousInPlaylist](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#start-vlcmediaplayerpreviousinplaylist) | vlcback, vlcprev | Moves to the previous item in the VLC Media Player playlist. |
| [Stop-TextToSpeech](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#stop-texttospeech) | sst | Immediately stops any ongoing text-to-speech output. |
| [Switch-VlcMediaPlayerMute](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#switch-vlcmediaplayermute) | vlcmute, vlcunmute | Toggles the mute state of the VLC Media Player. |
| [Switch-VLCMediaPlayerPaused](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#switch-vlcmediaplayerpaused) | vlcpause, vlcplay | Toggles the pause/play state of the VLC Media Player. |
| [Switch-VlcMediaPlayerRepeat](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#switch-vlcmediaplayerrepeat) | vlcrepeat | Toggles the repeat mode in VLC Media Player. |
| [UtcNow](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#utcnow) | &nbsp; | Gets the current UTC (Coordinated Universal Time) date and time. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Console/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Console.Spotify

**A Windows PowerShell module for enhancing the commandline experience**

### Cmdlet Index

| Command | Aliases | Description |
| --- | --- | --- |
| [Add-SpotifyNewPlaylist](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#add-spotifynewplaylist) | newplaylist | Creates a new Spotify playlist with customizable settings. |
| [Add-SpotifyTracksToLiked](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#add-spotifytrackstoliked) | like | Adds tracks to the user's Spotify liked songs library. |
| [Add-SpotifyTracksToPlaylist](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#add-spotifytrackstoplaylist) | addtoplaylist | Adds tracks to a Spotify playlist. |
| [Connect-SpotifyApiToken](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#connect-spotifyapitoken) | &nbsp; | Authenticates with Spotify API using OAuth flow to obtain an access token. |
| [Enable-Screensaver](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#enable-screensaver) | &nbsp; | Starts the configured Windows screensaver. |
| [Get-IsSpeaking](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#get-isspeaking) | iss | Returns true if the text-to-speech engine is speaking. |
| [Get-SpotifyActiveDevice](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#get-spotifyactivedevice) | &nbsp; | Returns all currently active Spotify devices for the current user. |
| [Get-SpotifyApiToken](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#get-spotifyapitoken) | &nbsp; | Retrieves or generates a valid Spotify API authentication token. |
| [Get-SpotifyCurrentlyPlaying](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#get-spotifycurrentlyplaying) | gcp | Returns information about the currently playing track on Spotify. |
| [Get-SpotifyDevice](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#get-spotifydevice) | Get-SpotifyDevices | Returns all currently available Spotify devices for current user. |
| [Get-SpotifyLikedTrack](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#get-spotifylikedtrack) | liked | Retrieves all tracks saved in the user's Spotify Library. |
| [Get-SpotifyLyrics](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#get-spotifylyrics) | lyrics | Retrieves lyrics for Spotify tracks from Musixmatch.com |
| [Get-SpotifyPlaylistIdsByName](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#get-spotifyplaylistidsbyname) | &nbsp; | Retrieves Spotify playlist IDs by their names. |
| [Get-SpotifyPlaylistTrack](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#get-spotifyplaylisttrack) | getplaylist | Returns all tracks from a Spotify playlist. |
| [Get-SpotifyTrackAudioFeatures](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#get-spotifytrackaudiofeatures) | audiofeatures | Retrieves audio feature information for one or more Spotify tracks. |
| [Get-SpotifyTrackById](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#get-spotifytrackbyid) | gettrack | Retrieves detailed track information from Spotify using a track ID. |
| [Get-SpotifyUserPlaylists](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#get-spotifyuserplaylists) | gupl | Returns a collection of Spotify playlists owned by the current user. |
| [Move-SpotifyLikedTracksToPlaylist](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#move-spotifylikedtrackstoplaylist) | moveliked | Moves all liked tracks from your Spotify library to specified playlist(s) |
| [New-MicrosoftShellTab](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#new-microsoftshelltab) | x | Creates a new Windows Terminal tab running PowerShell. |
| [Now](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#now) | &nbsp; | Returns the current system date and time as a DateTime object. |
| [Open-MediaFile](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#open-mediafile) | findmedia, media, vlcmedia | &nbsp; |
| [Open-VlcMediaPlayer](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#open-vlcmediaplayer) | vlc | Launches and controls VLC Media Player with extensive configuration options. |
| [Open-VlcMediaPlayerLyrics](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#open-vlcmediaplayerlyrics) | vlclyrics | Opens a web browser to search for lyrics of currently playing VLC media. |
| [Remove-SpotifyTracksFromLiked](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#remove-spotifytracksfromliked) | dislike | Removes tracks from the user's Spotify Library (Liked Songs). |
| [Remove-SpotifyTracksFromPlaylist](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#remove-spotifytracksfromplaylist) | removefromplaylist | Removes tracks from a Spotify playlist. |
| [SayDate](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#saydate) | &nbsp; | Speaks the current date using text-to-speech synthesis. |
| [SayTime](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#saytime) | &nbsp; | Announces the current time using text-to-speech. |
| [Search-Spotify](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#search-spotify) | fm, sm | Performs a Spotify search and returns matching items. |
| [Search-SpotifyAndEnqueue](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#search-spotifyandenqueue) | fmq, smq | Searches Spotify and adds the first matching item to the playback queue. |
| [Search-SpotifyAndPlay](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#search-spotifyandplay) | fmp, smp | Performs a Spotify search and plays the first found item. |
| [Set-LocationParent](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-locationparent) | .. | Changes the current location to the parent directory and lists its contents. |
| [Set-LocationParent2](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-locationparent2) | ... | Navigates up two directory levels in the file system hierarchy. |
| [Set-LocationParent3](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-locationparent3) | .... | Navigates up three directory levels in the file system hierarchy. |
| [Set-LocationParent4](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-locationparent4) | ..... | Navigates up four directory levels in the filesystem hierarchy. |
| [Set-LocationParent5](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-locationparent5) | ...... | Navigates up five directory levels in the file system hierarchy. |
| [Set-MonitorPowerOff](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-monitorpoweroff) | poweroff | Turns off power to all connected monitors. |
| [Set-MonitorPowerOn](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-monitorpoweron) | wake-monitor | Turns the monitor power on. |
| [Set-SpotifyActiveDevice](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-spotifyactivedevice) | Set-SpotifyDevice | Sets the active Spotify playback device. |
| [Set-SpotifyApiToken](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-spotifyapitoken) | &nbsp; | Caches a Spotify API token for later use in the local configuration. |
| [Set-SpotifyNext](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-spotifynext) | next, skip | Skips to next track on Spotify. |
| [Set-SpotifyPause](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-spotifypause) | pausemusic, Resume-Music | Pauses Spotify playback |
| [Set-SpotifyPlaylistDetails](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-spotifyplaylistdetails) | spld | Sets the main properties of a Spotify playlist. |
| [Set-SpotifyPlaylistOrder](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-spotifyplaylistorder) | &nbsp; | &nbsp; |
| [Set-SpotifyPrevious](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-spotifyprevious) | prev, previous | Skips to the previous track in Spotify playback. |
| [Set-SpotifyRepeatContext](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-spotifyrepeatcontext) | repeat | Enables playlist repeat mode for Spotify playback. |
| [Set-SpotifyRepeatOff](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-spotifyrepeatoff) | norepeat, repeatoff | Disables Spotify repeat mode for the currently active device. |
| [Set-SpotifyRepeatSong](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-spotifyrepeatsong) | repeatsong | Enables song repeat mode in Spotify. |
| [Set-SpotifyShuffleOff](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-spotifyshuffleoff) | noshuffle, shuffleoff | Disables Spotify song-shuffle mode on the active device. |
| [Set-SpotifyShuffleOn](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-spotifyshuffleon) | shuffle, shuffleon | Enables Spotify song-shuffle mode. |
| [Set-SpotifyStart](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-spotifystart) | play, Start-Music | Starts Spotify playback on the currently active device. |
| [Set-SpotifyStop](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-spotifystop) | stop | Stops Spotify playback on the active device. |
| [Set-VLCPlayerFocused](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-vlcplayerfocused) | fvlc, showvlc, vlcf | Sets focus to the VLC media player window. |
| [Start-TextToSpeech](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#start-texttospeech) | say | Converts text to speech using the Windows Speech API. |
| [Start-VlcMediaPlayerNextInPlaylist](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#start-vlcmediaplayernextinplaylist) | vlcnext | Advances VLC Media Player to the next item in the current playlist. |
| [Start-VlcMediaPlayerPreviousInPlaylist](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#start-vlcmediaplayerpreviousinplaylist) | vlcback, vlcprev | Moves to the previous item in the VLC Media Player playlist. |
| [Stop-TextToSpeech](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#stop-texttospeech) | sst | Immediately stops any ongoing text-to-speech output. |
| [Switch-VlcMediaPlayerMute](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#switch-vlcmediaplayermute) | vlcmute, vlcunmute | Toggles the mute state of the VLC Media Player. |
| [Switch-VLCMediaPlayerPaused](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#switch-vlcmediaplayerpaused) | vlcpause, vlcplay | Toggles the pause/play state of the VLC Media Player. |
| [Switch-VlcMediaPlayerRepeat](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#switch-vlcmediaplayerrepeat) | vlcrepeat | Toggles the repeat mode in VLC Media Player. |
| [UtcNow](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#utcnow) | &nbsp; | Gets the current UTC (Coordinated Universal Time) date and time. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Console/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Console.Vlc

**A Windows PowerShell module for enhancing the commandline experience**

### Cmdlet Index

| Command | Aliases | Description |
| --- | --- | --- |
| [Add-SpotifyNewPlaylist](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#add-spotifynewplaylist) | newplaylist | Creates a new Spotify playlist with customizable settings. |
| [Add-SpotifyTracksToLiked](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#add-spotifytrackstoliked) | like | Adds tracks to the user's Spotify liked songs library. |
| [Add-SpotifyTracksToPlaylist](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#add-spotifytrackstoplaylist) | addtoplaylist | Adds tracks to a Spotify playlist. |
| [Connect-SpotifyApiToken](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#connect-spotifyapitoken) | &nbsp; | Authenticates with Spotify API using OAuth flow to obtain an access token. |
| [Enable-Screensaver](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#enable-screensaver) | &nbsp; | Starts the configured Windows screensaver. |
| [Get-IsSpeaking](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#get-isspeaking) | iss | Returns true if the text-to-speech engine is speaking. |
| [Get-SpotifyActiveDevice](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#get-spotifyactivedevice) | &nbsp; | Returns all currently active Spotify devices for the current user. |
| [Get-SpotifyApiToken](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#get-spotifyapitoken) | &nbsp; | Retrieves or generates a valid Spotify API authentication token. |
| [Get-SpotifyCurrentlyPlaying](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#get-spotifycurrentlyplaying) | gcp | Returns information about the currently playing track on Spotify. |
| [Get-SpotifyDevice](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#get-spotifydevice) | Get-SpotifyDevices | Returns all currently available Spotify devices for current user. |
| [Get-SpotifyLikedTrack](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#get-spotifylikedtrack) | liked | Retrieves all tracks saved in the user's Spotify Library. |
| [Get-SpotifyLyrics](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#get-spotifylyrics) | lyrics | Retrieves lyrics for Spotify tracks from Musixmatch.com |
| [Get-SpotifyPlaylistIdsByName](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#get-spotifyplaylistidsbyname) | &nbsp; | Retrieves Spotify playlist IDs by their names. |
| [Get-SpotifyPlaylistTrack](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#get-spotifyplaylisttrack) | getplaylist | Returns all tracks from a Spotify playlist. |
| [Get-SpotifyTrackAudioFeatures](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#get-spotifytrackaudiofeatures) | audiofeatures | Retrieves audio feature information for one or more Spotify tracks. |
| [Get-SpotifyTrackById](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#get-spotifytrackbyid) | gettrack | Retrieves detailed track information from Spotify using a track ID. |
| [Get-SpotifyUserPlaylists](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#get-spotifyuserplaylists) | gupl | Returns a collection of Spotify playlists owned by the current user. |
| [Move-SpotifyLikedTracksToPlaylist](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#move-spotifylikedtrackstoplaylist) | moveliked | Moves all liked tracks from your Spotify library to specified playlist(s) |
| [New-MicrosoftShellTab](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#new-microsoftshelltab) | x | Creates a new Windows Terminal tab running PowerShell. |
| [Now](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#now) | &nbsp; | Returns the current system date and time as a DateTime object. |
| [Open-MediaFile](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#open-mediafile) | findmedia, media, vlcmedia | &nbsp; |
| [Open-VlcMediaPlayer](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#open-vlcmediaplayer) | vlc | Launches and controls VLC Media Player with extensive configuration options. |
| [Open-VlcMediaPlayerLyrics](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#open-vlcmediaplayerlyrics) | vlclyrics | Opens a web browser to search for lyrics of currently playing VLC media. |
| [Remove-SpotifyTracksFromLiked](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#remove-spotifytracksfromliked) | dislike | Removes tracks from the user's Spotify Library (Liked Songs). |
| [Remove-SpotifyTracksFromPlaylist](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#remove-spotifytracksfromplaylist) | removefromplaylist | Removes tracks from a Spotify playlist. |
| [SayDate](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#saydate) | &nbsp; | Speaks the current date using text-to-speech synthesis. |
| [SayTime](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#saytime) | &nbsp; | Announces the current time using text-to-speech. |
| [Search-Spotify](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#search-spotify) | fm, sm | Performs a Spotify search and returns matching items. |
| [Search-SpotifyAndEnqueue](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#search-spotifyandenqueue) | fmq, smq | Searches Spotify and adds the first matching item to the playback queue. |
| [Search-SpotifyAndPlay](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#search-spotifyandplay) | fmp, smp | Performs a Spotify search and plays the first found item. |
| [Set-LocationParent](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-locationparent) | .. | Changes the current location to the parent directory and lists its contents. |
| [Set-LocationParent2](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-locationparent2) | ... | Navigates up two directory levels in the file system hierarchy. |
| [Set-LocationParent3](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-locationparent3) | .... | Navigates up three directory levels in the file system hierarchy. |
| [Set-LocationParent4](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-locationparent4) | ..... | Navigates up four directory levels in the filesystem hierarchy. |
| [Set-LocationParent5](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-locationparent5) | ...... | Navigates up five directory levels in the file system hierarchy. |
| [Set-MonitorPowerOff](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-monitorpoweroff) | poweroff | Turns off power to all connected monitors. |
| [Set-MonitorPowerOn](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-monitorpoweron) | wake-monitor | Turns the monitor power on. |
| [Set-SpotifyActiveDevice](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-spotifyactivedevice) | Set-SpotifyDevice | Sets the active Spotify playback device. |
| [Set-SpotifyApiToken](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-spotifyapitoken) | &nbsp; | Caches a Spotify API token for later use in the local configuration. |
| [Set-SpotifyNext](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-spotifynext) | next, skip | Skips to next track on Spotify. |
| [Set-SpotifyPause](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-spotifypause) | pausemusic, Resume-Music | Pauses Spotify playback |
| [Set-SpotifyPlaylistDetails](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-spotifyplaylistdetails) | spld | Sets the main properties of a Spotify playlist. |
| [Set-SpotifyPlaylistOrder](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-spotifyplaylistorder) | &nbsp; | &nbsp; |
| [Set-SpotifyPrevious](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-spotifyprevious) | prev, previous | Skips to the previous track in Spotify playback. |
| [Set-SpotifyRepeatContext](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-spotifyrepeatcontext) | repeat | Enables playlist repeat mode for Spotify playback. |
| [Set-SpotifyRepeatOff](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-spotifyrepeatoff) | norepeat, repeatoff | Disables Spotify repeat mode for the currently active device. |
| [Set-SpotifyRepeatSong](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-spotifyrepeatsong) | repeatsong | Enables song repeat mode in Spotify. |
| [Set-SpotifyShuffleOff](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-spotifyshuffleoff) | noshuffle, shuffleoff | Disables Spotify song-shuffle mode on the active device. |
| [Set-SpotifyShuffleOn](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-spotifyshuffleon) | shuffle, shuffleon | Enables Spotify song-shuffle mode. |
| [Set-SpotifyStart](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-spotifystart) | play, Start-Music | Starts Spotify playback on the currently active device. |
| [Set-SpotifyStop](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-spotifystop) | stop | Stops Spotify playback on the active device. |
| [Set-VLCPlayerFocused](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#set-vlcplayerfocused) | fvlc, showvlc, vlcf | Sets focus to the VLC media player window. |
| [Start-TextToSpeech](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#start-texttospeech) | say | Converts text to speech using the Windows Speech API. |
| [Start-VlcMediaPlayerNextInPlaylist](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#start-vlcmediaplayernextinplaylist) | vlcnext | Advances VLC Media Player to the next item in the current playlist. |
| [Start-VlcMediaPlayerPreviousInPlaylist](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#start-vlcmediaplayerpreviousinplaylist) | vlcback, vlcprev | Moves to the previous item in the VLC Media Player playlist. |
| [Stop-TextToSpeech](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#stop-texttospeech) | sst | Immediately stops any ongoing text-to-speech output. |
| [Switch-VlcMediaPlayerMute](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#switch-vlcmediaplayermute) | vlcmute, vlcunmute | Toggles the mute state of the VLC Media Player. |
| [Switch-VLCMediaPlayerPaused](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#switch-vlcmediaplayerpaused) | vlcpause, vlcplay | Toggles the pause/play state of the VLC Media Player. |
| [Switch-VlcMediaPlayerRepeat](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#switch-vlcmediaplayerrepeat) | vlcrepeat | Toggles the repeat mode in VLC Media Player. |
| [UtcNow](https://github.com/genXdev/GenXdev.Console/blob/main/README.md#utcnow) | &nbsp; | Gets the current UTC (Coordinated Universal Time) date and time. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Console/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Data

**A Windows PowerShell module for enhancing the commandline experience**

### Cmdlet Index

| Command | Aliases | Description |
| --- | --- | --- |
| [EnsureSQLiteStudioInstalled](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#ensuresqlitestudioinstalled) | &nbsp; | Ensures SQLiteStudio is installed and accessible from the command line. |
| [Get-GenXdevPreference](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-genxdevpreference) | getPreference | Retrieves a preference value from the GenXdev preferences store. |
| [Get-GenXdevPreferenceNames](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-genxdevpreferencenames) | getPreferenceNames | Gets all preference names from session storage and database stores. |
| [Get-GenXdevPreferencesDatabasePath](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-genxdevpreferencesdatabasepath) | &nbsp; | Gets the configured database path for preference data files used in GenXdev.Data operations. |
| [Get-KeyValueStoreNames](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-keyvaluestorenames) | getstorenames | Retrieves a list of all available key-value store names from the database. |
| [Get-SQLiteSchema](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqliteschema) | &nbsp; | Retrieves the complete schema information from a SQLite database. |
| [Get-SQLiteTableColumnData](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqlitetablecolumndata) | &nbsp; | Retrieves data from a specific column in a SQLite database table. |
| [Get-SQLiteTableData](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqlitetabledata) | &nbsp; | Retrieves data from a SQLite database table with optional record limiting. |
| [Get-SQLiteTables](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqlitetables) | &nbsp; | Retrieves a list of table names from a SQLite database. |
| [Get-SQLiteTableSchema](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqlitetableschema) | &nbsp; | Retrieves the schema information for a specified SQLite table. |
| [Get-SQLiteTransaction](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqlitetransaction) | getsqltx, newsqltx | Creates and returns a SQLite transaction object for batch operations. |
| [Get-SQLiteViewColumnData](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqliteviewcolumndata) | &nbsp; | Retrieves column data from a SQLite view with optional record limiting. |
| [Get-SQLiteViewData](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqliteviewdata) | &nbsp; | Retrieves data from a SQLite database view with optional record limiting. |
| [Get-SQLiteViews](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqliteviews) | &nbsp; | Retrieves a list of views from a SQLite database. |
| [Get-SQLiteViewSchema](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqliteviewschema) | &nbsp; | Retrieves the SQL schema definition for a SQLite view. |
| [Get-StoreKeys](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-storekeys) | getkeys | Retrieves all key names for a given key-value store. |
| [Get-ValueByKeyFromStore](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-valuebykeyfromstore) | getvalue | Retrieves a value from a key-value store database. |
| [Initialize-KeyValueStores](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#initialize-keyvaluestores) | &nbsp; | Initializes and synchronizes KeyValueStore databases between local and OneDrive. |
| [Invoke-SQLiteQuery](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#invoke-sqlitequery) | &nbsp; | Executes one or more SQL queries against a SQLite database with transaction support. |
| [Invoke-SQLiteStudio](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#invoke-sqlitestudio) | &nbsp; | Executes SQLite database queries with support for parameters and transactions. |
| [Invoke-SqlServerQuery](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#invoke-sqlserverquery) | &nbsp; | Executes SQL queries against a SQL Server database with transaction support. |
| [New-SQLiteDatabase](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#new-sqlitedatabase) | nsqldb | Creates a new SQLite database file. |
| [Remove-GenXdevPreference](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#remove-genxdevpreference) | removePreference | Removes a preference value from the GenXdev preferences store. |
| [Remove-KeyFromStore](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#remove-keyfromstore) | removekey | Deletes a key from the specified key-value store. |
| [Remove-KeyValueStore](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#remove-keyvaluestore) | &nbsp; | Removes a key-value store from the database. |
| [Set-GenXdevDefaultPreference](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#set-genxdevdefaultpreference) | setPreferenceDefault | Sets a default preference value in the GenXdev preferences store. |
| [Set-GenXdevPreference](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#set-genxdevpreference) | setPreference | Sets a preference value in the GenXdev preferences store. |
| [Set-GenXdevPreferencesDatabasePath](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#set-genxdevpreferencesdatabasepath) | &nbsp; | Sets the database path for preferences used in GenXdev.Data operations. |
| [Set-ValueByKeyInStore](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#set-valuebykeyinstore) | setvalue | Manages key-value pairs in a SQLite database store. |
| [Sync-KeyValueStore](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#sync-keyvaluestore) | &nbsp; | Synchronizes local and OneDrive key-value store databases. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Data/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Data.KeyValueStore

**A Windows PowerShell module for enhancing the commandline experience**

### Cmdlet Index

| Command | Aliases | Description |
| --- | --- | --- |
| [EnsureSQLiteStudioInstalled](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#ensuresqlitestudioinstalled) | &nbsp; | Ensures SQLiteStudio is installed and accessible from the command line. |
| [Get-GenXdevPreference](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-genxdevpreference) | getPreference | Retrieves a preference value from the GenXdev preferences store. |
| [Get-GenXdevPreferenceNames](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-genxdevpreferencenames) | getPreferenceNames | Gets all preference names from session storage and database stores. |
| [Get-GenXdevPreferencesDatabasePath](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-genxdevpreferencesdatabasepath) | &nbsp; | Gets the configured database path for preference data files used in GenXdev.Data operations. |
| [Get-KeyValueStoreNames](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-keyvaluestorenames) | getstorenames | Retrieves a list of all available key-value store names from the database. |
| [Get-SQLiteSchema](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqliteschema) | &nbsp; | Retrieves the complete schema information from a SQLite database. |
| [Get-SQLiteTableColumnData](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqlitetablecolumndata) | &nbsp; | Retrieves data from a specific column in a SQLite database table. |
| [Get-SQLiteTableData](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqlitetabledata) | &nbsp; | Retrieves data from a SQLite database table with optional record limiting. |
| [Get-SQLiteTables](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqlitetables) | &nbsp; | Retrieves a list of table names from a SQLite database. |
| [Get-SQLiteTableSchema](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqlitetableschema) | &nbsp; | Retrieves the schema information for a specified SQLite table. |
| [Get-SQLiteTransaction](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqlitetransaction) | getsqltx, newsqltx | Creates and returns a SQLite transaction object for batch operations. |
| [Get-SQLiteViewColumnData](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqliteviewcolumndata) | &nbsp; | Retrieves column data from a SQLite view with optional record limiting. |
| [Get-SQLiteViewData](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqliteviewdata) | &nbsp; | Retrieves data from a SQLite database view with optional record limiting. |
| [Get-SQLiteViews](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqliteviews) | &nbsp; | Retrieves a list of views from a SQLite database. |
| [Get-SQLiteViewSchema](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqliteviewschema) | &nbsp; | Retrieves the SQL schema definition for a SQLite view. |
| [Get-StoreKeys](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-storekeys) | getkeys | Retrieves all key names for a given key-value store. |
| [Get-ValueByKeyFromStore](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-valuebykeyfromstore) | getvalue | Retrieves a value from a key-value store database. |
| [Initialize-KeyValueStores](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#initialize-keyvaluestores) | &nbsp; | Initializes and synchronizes KeyValueStore databases between local and OneDrive. |
| [Invoke-SQLiteQuery](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#invoke-sqlitequery) | &nbsp; | Executes one or more SQL queries against a SQLite database with transaction support. |
| [Invoke-SQLiteStudio](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#invoke-sqlitestudio) | &nbsp; | Executes SQLite database queries with support for parameters and transactions. |
| [Invoke-SqlServerQuery](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#invoke-sqlserverquery) | &nbsp; | Executes SQL queries against a SQL Server database with transaction support. |
| [New-SQLiteDatabase](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#new-sqlitedatabase) | nsqldb | Creates a new SQLite database file. |
| [Remove-GenXdevPreference](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#remove-genxdevpreference) | removePreference | Removes a preference value from the GenXdev preferences store. |
| [Remove-KeyFromStore](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#remove-keyfromstore) | removekey | Deletes a key from the specified key-value store. |
| [Remove-KeyValueStore](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#remove-keyvaluestore) | &nbsp; | Removes a key-value store from the database. |
| [Set-GenXdevDefaultPreference](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#set-genxdevdefaultpreference) | setPreferenceDefault | Sets a default preference value in the GenXdev preferences store. |
| [Set-GenXdevPreference](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#set-genxdevpreference) | setPreference | Sets a preference value in the GenXdev preferences store. |
| [Set-GenXdevPreferencesDatabasePath](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#set-genxdevpreferencesdatabasepath) | &nbsp; | Sets the database path for preferences used in GenXdev.Data operations. |
| [Set-ValueByKeyInStore](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#set-valuebykeyinstore) | setvalue | Manages key-value pairs in a SQLite database store. |
| [Sync-KeyValueStore](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#sync-keyvaluestore) | &nbsp; | Synchronizes local and OneDrive key-value store databases. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Data/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Data.Preferences

**A Windows PowerShell module for enhancing the commandline experience**

### Cmdlet Index

| Command | Aliases | Description |
| --- | --- | --- |
| [EnsureSQLiteStudioInstalled](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#ensuresqlitestudioinstalled) | &nbsp; | Ensures SQLiteStudio is installed and accessible from the command line. |
| [Get-GenXdevPreference](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-genxdevpreference) | getPreference | Retrieves a preference value from the GenXdev preferences store. |
| [Get-GenXdevPreferenceNames](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-genxdevpreferencenames) | getPreferenceNames | Gets all preference names from session storage and database stores. |
| [Get-GenXdevPreferencesDatabasePath](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-genxdevpreferencesdatabasepath) | &nbsp; | Gets the configured database path for preference data files used in GenXdev.Data operations. |
| [Get-KeyValueStoreNames](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-keyvaluestorenames) | getstorenames | Retrieves a list of all available key-value store names from the database. |
| [Get-SQLiteSchema](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqliteschema) | &nbsp; | Retrieves the complete schema information from a SQLite database. |
| [Get-SQLiteTableColumnData](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqlitetablecolumndata) | &nbsp; | Retrieves data from a specific column in a SQLite database table. |
| [Get-SQLiteTableData](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqlitetabledata) | &nbsp; | Retrieves data from a SQLite database table with optional record limiting. |
| [Get-SQLiteTables](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqlitetables) | &nbsp; | Retrieves a list of table names from a SQLite database. |
| [Get-SQLiteTableSchema](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqlitetableschema) | &nbsp; | Retrieves the schema information for a specified SQLite table. |
| [Get-SQLiteTransaction](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqlitetransaction) | getsqltx, newsqltx | Creates and returns a SQLite transaction object for batch operations. |
| [Get-SQLiteViewColumnData](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqliteviewcolumndata) | &nbsp; | Retrieves column data from a SQLite view with optional record limiting. |
| [Get-SQLiteViewData](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqliteviewdata) | &nbsp; | Retrieves data from a SQLite database view with optional record limiting. |
| [Get-SQLiteViews](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqliteviews) | &nbsp; | Retrieves a list of views from a SQLite database. |
| [Get-SQLiteViewSchema](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqliteviewschema) | &nbsp; | Retrieves the SQL schema definition for a SQLite view. |
| [Get-StoreKeys](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-storekeys) | getkeys | Retrieves all key names for a given key-value store. |
| [Get-ValueByKeyFromStore](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-valuebykeyfromstore) | getvalue | Retrieves a value from a key-value store database. |
| [Initialize-KeyValueStores](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#initialize-keyvaluestores) | &nbsp; | Initializes and synchronizes KeyValueStore databases between local and OneDrive. |
| [Invoke-SQLiteQuery](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#invoke-sqlitequery) | &nbsp; | Executes one or more SQL queries against a SQLite database with transaction support. |
| [Invoke-SQLiteStudio](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#invoke-sqlitestudio) | &nbsp; | Executes SQLite database queries with support for parameters and transactions. |
| [Invoke-SqlServerQuery](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#invoke-sqlserverquery) | &nbsp; | Executes SQL queries against a SQL Server database with transaction support. |
| [New-SQLiteDatabase](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#new-sqlitedatabase) | nsqldb | Creates a new SQLite database file. |
| [Remove-GenXdevPreference](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#remove-genxdevpreference) | removePreference | Removes a preference value from the GenXdev preferences store. |
| [Remove-KeyFromStore](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#remove-keyfromstore) | removekey | Deletes a key from the specified key-value store. |
| [Remove-KeyValueStore](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#remove-keyvaluestore) | &nbsp; | Removes a key-value store from the database. |
| [Set-GenXdevDefaultPreference](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#set-genxdevdefaultpreference) | setPreferenceDefault | Sets a default preference value in the GenXdev preferences store. |
| [Set-GenXdevPreference](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#set-genxdevpreference) | setPreference | Sets a preference value in the GenXdev preferences store. |
| [Set-GenXdevPreferencesDatabasePath](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#set-genxdevpreferencesdatabasepath) | &nbsp; | Sets the database path for preferences used in GenXdev.Data operations. |
| [Set-ValueByKeyInStore](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#set-valuebykeyinstore) | setvalue | Manages key-value pairs in a SQLite database store. |
| [Sync-KeyValueStore](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#sync-keyvaluestore) | &nbsp; | Synchronizes local and OneDrive key-value store databases. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Data/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Data.SQLite

**A Windows PowerShell module for enhancing the commandline experience**

### Cmdlet Index

| Command | Aliases | Description |
| --- | --- | --- |
| [EnsureSQLiteStudioInstalled](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#ensuresqlitestudioinstalled) | &nbsp; | Ensures SQLiteStudio is installed and accessible from the command line. |
| [Get-GenXdevPreference](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-genxdevpreference) | getPreference | Retrieves a preference value from the GenXdev preferences store. |
| [Get-GenXdevPreferenceNames](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-genxdevpreferencenames) | getPreferenceNames | Gets all preference names from session storage and database stores. |
| [Get-GenXdevPreferencesDatabasePath](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-genxdevpreferencesdatabasepath) | &nbsp; | Gets the configured database path for preference data files used in GenXdev.Data operations. |
| [Get-KeyValueStoreNames](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-keyvaluestorenames) | getstorenames | Retrieves a list of all available key-value store names from the database. |
| [Get-SQLiteSchema](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqliteschema) | &nbsp; | Retrieves the complete schema information from a SQLite database. |
| [Get-SQLiteTableColumnData](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqlitetablecolumndata) | &nbsp; | Retrieves data from a specific column in a SQLite database table. |
| [Get-SQLiteTableData](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqlitetabledata) | &nbsp; | Retrieves data from a SQLite database table with optional record limiting. |
| [Get-SQLiteTables](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqlitetables) | &nbsp; | Retrieves a list of table names from a SQLite database. |
| [Get-SQLiteTableSchema](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqlitetableschema) | &nbsp; | Retrieves the schema information for a specified SQLite table. |
| [Get-SQLiteTransaction](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqlitetransaction) | getsqltx, newsqltx | Creates and returns a SQLite transaction object for batch operations. |
| [Get-SQLiteViewColumnData](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqliteviewcolumndata) | &nbsp; | Retrieves column data from a SQLite view with optional record limiting. |
| [Get-SQLiteViewData](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqliteviewdata) | &nbsp; | Retrieves data from a SQLite database view with optional record limiting. |
| [Get-SQLiteViews](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqliteviews) | &nbsp; | Retrieves a list of views from a SQLite database. |
| [Get-SQLiteViewSchema](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqliteviewschema) | &nbsp; | Retrieves the SQL schema definition for a SQLite view. |
| [Get-StoreKeys](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-storekeys) | getkeys | Retrieves all key names for a given key-value store. |
| [Get-ValueByKeyFromStore](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-valuebykeyfromstore) | getvalue | Retrieves a value from a key-value store database. |
| [Initialize-KeyValueStores](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#initialize-keyvaluestores) | &nbsp; | Initializes and synchronizes KeyValueStore databases between local and OneDrive. |
| [Invoke-SQLiteQuery](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#invoke-sqlitequery) | &nbsp; | Executes one or more SQL queries against a SQLite database with transaction support. |
| [Invoke-SQLiteStudio](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#invoke-sqlitestudio) | &nbsp; | Executes SQLite database queries with support for parameters and transactions. |
| [Invoke-SqlServerQuery](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#invoke-sqlserverquery) | &nbsp; | Executes SQL queries against a SQL Server database with transaction support. |
| [New-SQLiteDatabase](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#new-sqlitedatabase) | nsqldb | Creates a new SQLite database file. |
| [Remove-GenXdevPreference](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#remove-genxdevpreference) | removePreference | Removes a preference value from the GenXdev preferences store. |
| [Remove-KeyFromStore](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#remove-keyfromstore) | removekey | Deletes a key from the specified key-value store. |
| [Remove-KeyValueStore](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#remove-keyvaluestore) | &nbsp; | Removes a key-value store from the database. |
| [Set-GenXdevDefaultPreference](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#set-genxdevdefaultpreference) | setPreferenceDefault | Sets a default preference value in the GenXdev preferences store. |
| [Set-GenXdevPreference](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#set-genxdevpreference) | setPreference | Sets a preference value in the GenXdev preferences store. |
| [Set-GenXdevPreferencesDatabasePath](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#set-genxdevpreferencesdatabasepath) | &nbsp; | Sets the database path for preferences used in GenXdev.Data operations. |
| [Set-ValueByKeyInStore](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#set-valuebykeyinstore) | setvalue | Manages key-value pairs in a SQLite database store. |
| [Sync-KeyValueStore](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#sync-keyvaluestore) | &nbsp; | Synchronizes local and OneDrive key-value store databases. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Data/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Data.SqlServer

**A Windows PowerShell module for enhancing the commandline experience**

### Cmdlet Index

| Command | Aliases | Description |
| --- | --- | --- |
| [EnsureSQLiteStudioInstalled](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#ensuresqlitestudioinstalled) | &nbsp; | Ensures SQLiteStudio is installed and accessible from the command line. |
| [Get-GenXdevPreference](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-genxdevpreference) | getPreference | Retrieves a preference value from the GenXdev preferences store. |
| [Get-GenXdevPreferenceNames](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-genxdevpreferencenames) | getPreferenceNames | Gets all preference names from session storage and database stores. |
| [Get-GenXdevPreferencesDatabasePath](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-genxdevpreferencesdatabasepath) | &nbsp; | Gets the configured database path for preference data files used in GenXdev.Data operations. |
| [Get-KeyValueStoreNames](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-keyvaluestorenames) | getstorenames | Retrieves a list of all available key-value store names from the database. |
| [Get-SQLiteSchema](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqliteschema) | &nbsp; | Retrieves the complete schema information from a SQLite database. |
| [Get-SQLiteTableColumnData](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqlitetablecolumndata) | &nbsp; | Retrieves data from a specific column in a SQLite database table. |
| [Get-SQLiteTableData](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqlitetabledata) | &nbsp; | Retrieves data from a SQLite database table with optional record limiting. |
| [Get-SQLiteTables](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqlitetables) | &nbsp; | Retrieves a list of table names from a SQLite database. |
| [Get-SQLiteTableSchema](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqlitetableschema) | &nbsp; | Retrieves the schema information for a specified SQLite table. |
| [Get-SQLiteTransaction](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqlitetransaction) | getsqltx, newsqltx | Creates and returns a SQLite transaction object for batch operations. |
| [Get-SQLiteViewColumnData](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqliteviewcolumndata) | &nbsp; | Retrieves column data from a SQLite view with optional record limiting. |
| [Get-SQLiteViewData](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqliteviewdata) | &nbsp; | Retrieves data from a SQLite database view with optional record limiting. |
| [Get-SQLiteViews](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqliteviews) | &nbsp; | Retrieves a list of views from a SQLite database. |
| [Get-SQLiteViewSchema](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-sqliteviewschema) | &nbsp; | Retrieves the SQL schema definition for a SQLite view. |
| [Get-StoreKeys](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-storekeys) | getkeys | Retrieves all key names for a given key-value store. |
| [Get-ValueByKeyFromStore](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#get-valuebykeyfromstore) | getvalue | Retrieves a value from a key-value store database. |
| [Initialize-KeyValueStores](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#initialize-keyvaluestores) | &nbsp; | Initializes and synchronizes KeyValueStore databases between local and OneDrive. |
| [Invoke-SQLiteQuery](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#invoke-sqlitequery) | &nbsp; | Executes one or more SQL queries against a SQLite database with transaction support. |
| [Invoke-SQLiteStudio](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#invoke-sqlitestudio) | &nbsp; | Executes SQLite database queries with support for parameters and transactions. |
| [Invoke-SqlServerQuery](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#invoke-sqlserverquery) | &nbsp; | Executes SQL queries against a SQL Server database with transaction support. |
| [New-SQLiteDatabase](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#new-sqlitedatabase) | nsqldb | Creates a new SQLite database file. |
| [Remove-GenXdevPreference](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#remove-genxdevpreference) | removePreference | Removes a preference value from the GenXdev preferences store. |
| [Remove-KeyFromStore](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#remove-keyfromstore) | removekey | Deletes a key from the specified key-value store. |
| [Remove-KeyValueStore](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#remove-keyvaluestore) | &nbsp; | Removes a key-value store from the database. |
| [Set-GenXdevDefaultPreference](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#set-genxdevdefaultpreference) | setPreferenceDefault | Sets a default preference value in the GenXdev preferences store. |
| [Set-GenXdevPreference](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#set-genxdevpreference) | setPreference | Sets a preference value in the GenXdev preferences store. |
| [Set-GenXdevPreferencesDatabasePath](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#set-genxdevpreferencesdatabasepath) | &nbsp; | Sets the database path for preferences used in GenXdev.Data operations. |
| [Set-ValueByKeyInStore](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#set-valuebykeyinstore) | setvalue | Manages key-value pairs in a SQLite database store. |
| [Sync-KeyValueStore](https://github.com/genXdev/GenXdev.Data/blob/main/README.md#sync-keyvaluestore) | &nbsp; | Synchronizes local and OneDrive key-value store databases. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Data/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.FileSystem

**A Windows PowerShell module for basic and advanced file management tasks**

### Cmdlet Index

| Command | Aliases | Description |
| --- | --- | --- |
| [EnsurePester](https://github.com/genXdev/GenXdev.FileSystem/blob/main/README.md#ensurepester) | &nbsp; | Ensures Pester testing framework is available for use. |
| [Expand-Path](https://github.com/genXdev/GenXdev.FileSystem/blob/main/README.md#expand-path) | ep | Expands any given file reference to a full pathname. |
| [Find-DuplicateFiles](https://github.com/genXdev/GenXdev.FileSystem/blob/main/README.md#find-duplicatefiles) | fdf | Find duplicate files across multiple directories based on configurable criteria. |
| [Find-Item](https://github.com/genXdev/GenXdev.FileSystem/blob/main/README.md#find-item) | l | Performs advanced file and directory searches with content filtering capabilities. |
| [Invoke-Fasti](https://github.com/genXdev/GenXdev.FileSystem/blob/main/README.md#invoke-fasti) | fasti | Extracts archive files in the current directory and deletes the originals. |
| [Move-ItemWithTracking](https://github.com/genXdev/GenXdev.FileSystem/blob/main/README.md#move-itemwithtracking) | &nbsp; | Moves files and directories while preserving filesystem links and references. |
| [Move-ToRecycleBin](https://github.com/genXdev/GenXdev.FileSystem/blob/main/README.md#move-torecyclebin) | recycle | Moves files and directories to the Windows Recycle Bin safely. |
| [Remove-AllItems](https://github.com/genXdev/GenXdev.FileSystem/blob/main/README.md#remove-allitems) | sdel | Recursively removes all content from a directory with advanced error handling. |
| [Remove-ItemWithFallback](https://github.com/genXdev/GenXdev.FileSystem/blob/main/README.md#remove-itemwithfallback) | rmf | Removes files or directories with multiple fallback mechanisms for reliable deletion. |
| [Remove-OnReboot](https://github.com/genXdev/GenXdev.FileSystem/blob/main/README.md#remove-onreboot) | &nbsp; | Marks files or directories for deletion during the next system boot. |
| [Rename-InProject](https://github.com/genXdev/GenXdev.FileSystem/blob/main/README.md#rename-inproject) | rip | Performs text replacement throughout a project directory. |
| [ResolveInputObjectFileNames](https://github.com/genXdev/GenXdev.FileSystem/blob/main/README.md#resolveinputobjectfilenames) | &nbsp; | &nbsp; |
| [Start-RoboCopy](https://github.com/genXdev/GenXdev.FileSystem/blob/main/README.md#start-robocopy) | rc, xc | Provides a PowerShell wrapper for Microsoft's Robust Copy (RoboCopy) utility. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.FileSystem/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Helpers

**A Windows PowerShell module with helpers mostly used by other GenXdev modules**

### Cmdlet Index

| Command | Aliases | Description |
| --- | --- | --- |
| [alignScript](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md#alignscript) | &nbsp; | Returns a string (with altered indentation) of a provided scriptblock string |
| [ConvertTo-HashTable](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md#convertto-hashtable) | &nbsp; | Converts a PSCustomObject to a HashTable recursively. |
| [ConvertTo-JsonEx](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md#convertto-jsonex) | tojsonex | Converts an object to a JSON string with extended options. |
| [EnsureGenXdev](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md#ensuregenxdev) | &nbsp; | &nbsp; |
| [EnsureNuGetAssembly](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md#ensurenugetassembly) | &nbsp; | Downloads and loads .NET assemblies from NuGet packages based on package key or ID. |
| [Get-DefaultWebLanguage](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md#get-defaultweblanguage) | &nbsp; | Gets the default web language key based on the system's current language settings. |
| [Get-FreeFallHeight](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md#get-freefallheight) | &nbsp; | Calculates the height fallen during free fall for a given time duration. |
| [Get-FreeFallTime](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md#get-freefalltime) | &nbsp; | Calculates the time it takes for an object to fall a specified distance. |
| [Get-GenXDevCmdlet](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md#get-genxdevcmdlet) | gcmds | Retrieves and lists all GenXdev cmdlets and their details. |
| [Get-ImageGeolocation](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md#get-imagegeolocation) | &nbsp; | Extracts geolocation data from an image file. |
| [Get-ImageMetadata](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md#get-imagemetadata) | &nbsp; | Extracts comprehensive metadata from an image file. |
| [Get-WebLanguageDictionary](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md#get-weblanguagedictionary) | &nbsp; | Returns a reversed dictionary for all languages supported by Google Search |
| [Import-GenXdevModules](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md#import-genxdevmodules) | reloadgenxdev | Imports all GenXdev PowerShell modules into the global scope. |
| [Initialize-SearchPaths](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md#initialize-searchpaths) | &nbsp; | Initializes and configures system search paths for package management. |
| [Invoke-OnEachGenXdevModule](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md#invoke-oneachgenxdevmodule) | foreach-genxdev-module-do | Executes a script block on each GenXdev module in the workspace. |
| [Out-Serial](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md#out-serial) | &nbsp; | Sends a string to a serial port |
| [Remove-JSONComments](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md#remove-jsoncomments) | &nbsp; | Removes comments from JSON content. |
| [Show-GenXDevCmdlet](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md#show-genxdevcmdlet) | cmds | Displays GenXdev PowerShell modules with their cmdlets and aliases. |
| [Show-Verb](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md#show-verb) | showverbs | Shows a short alphabetical list of all PowerShell verbs. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Helpers.Math.Physics

**A Windows PowerShell module with helpers mostly used by other GenXdev modules**

### Cmdlet Index

| Command | Aliases | Description |
| --- | --- | --- |
| [_EnsureTypes](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md#ensuretypes) | &nbsp; | &nbsp; |
| [alignScript](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md#alignscript) | &nbsp; | Returns a string (with altered indentation) of a provided scriptblock string |
| [ConvertTo-HashTable](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md#convertto-hashtable) | &nbsp; | Converts a PSCustomObject to a HashTable recursively. |
| [ConvertTo-JsonEx](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md#convertto-jsonex) | tojsonex | Converts an object to a JSON string with extended options. |
| [EnsureGenXdev](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md#ensuregenxdev) | &nbsp; | &nbsp; |
| [EnsureNuGetAssembly](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md#ensurenugetassembly) | &nbsp; | Downloads and loads .NET assemblies from NuGet packages based on package key or ID. |
| [Get-DefaultWebLanguage](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md#get-defaultweblanguage) | &nbsp; | Gets the default web language key based on the system's current language settings. |
| [Get-FreeFallHeight](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md#get-freefallheight) | &nbsp; | Calculates the height fallen during free fall for a given time duration. |
| [Get-FreeFallTime](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md#get-freefalltime) | &nbsp; | Calculates the time it takes for an object to fall a specified distance. |
| [Get-GenXDevCmdlet](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md#get-genxdevcmdlet) | gcmds | Retrieves and lists all GenXdev cmdlets and their details. |
| [Get-ImageGeolocation](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md#get-imagegeolocation) | &nbsp; | Extracts geolocation data from an image file. |
| [Get-ImageMetadata](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md#get-imagemetadata) | &nbsp; | Extracts comprehensive metadata from an image file. |
| [Get-WebLanguageDictionary](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md#get-weblanguagedictionary) | &nbsp; | Returns a reversed dictionary for all languages supported by Google Search |
| [Import-GenXdevModules](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md#import-genxdevmodules) | reloadgenxdev | Imports all GenXdev PowerShell modules into the global scope. |
| [Initialize-SearchPaths](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md#initialize-searchpaths) | &nbsp; | Initializes and configures system search paths for package management. |
| [Invoke-OnEachGenXdevModule](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md#invoke-oneachgenxdevmodule) | foreach-genxdev-module-do | Executes a script block on each GenXdev module in the workspace. |
| [Out-Serial](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md#out-serial) | &nbsp; | Sends a string to a serial port |
| [Remove-JSONComments](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md#remove-jsoncomments) | &nbsp; | Removes comments from JSON content. |
| [Show-GenXDevCmdlet](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md#show-genxdevcmdlet) | cmds | Displays GenXdev PowerShell modules with their cmdlets and aliases. |
| [Show-Verb](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md#show-verb) | showverbs | Shows a short alphabetical list of all PowerShell verbs. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Media

**A Windows PowerShell module that helps with converting media files like pictures and video files**

### Cmdlet Index

| Command | Aliases | Description |
| --- | --- | --- |
| [EnsureYtdlp](https://github.com/genXdev/GenXdev.Media/blob/main/README.md#ensureytdlp) | &nbsp; | Ensures yt-dlp is installed and available in the default WSL image. |
| [Invoke-YTDlpSaveVideo](https://github.com/genXdev/GenXdev.Media/blob/main/README.md#invoke-ytdlpsavevideo) | Save-Video, savevideo | Downloads a video from a specified URL using yt-dlp and saves metadata. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Media/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Media.ffmpeg

**A Windows PowerShell module that helps with converting media files like pictures and video files**

### Cmdlet Index

| Command | Aliases | Description |
| --- | --- | --- |
| [EnsureYtdlp](https://github.com/genXdev/GenXdev.Media/blob/main/README.md#ensureytdlp) | &nbsp; | Ensures yt-dlp is installed and available in the default WSL image. |
| [Invoke-YTDlpSaveVideo](https://github.com/genXdev/GenXdev.Media/blob/main/README.md#invoke-ytdlpsavevideo) | Save-Video, savevideo | Downloads a video from a specified URL using yt-dlp and saves metadata. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Media/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Media.ytdlp

**A Windows PowerShell module that helps with converting media files like pictures and video files**

### Cmdlet Index

| Command | Aliases | Description |
| --- | --- | --- |
| [EnsureYtdlp](https://github.com/genXdev/GenXdev.Media/blob/main/README.md#ensureytdlp) | &nbsp; | Ensures yt-dlp is installed and available in the default WSL image. |
| [Invoke-YTDlpSaveVideo](https://github.com/genXdev/GenXdev.Media/blob/main/README.md#invoke-ytdlpsavevideo) | Save-Video, savevideo | Downloads a video from a specified URL using yt-dlp and saves metadata. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Media/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Queries

**A Windows PowerShell module for finding resources and information on the internet**

### Cmdlet Index

| Command | Aliases | Description |
| --- | --- | --- |
| [Clear-YoutubeWatched](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#clear-youtubewatched) | &nbsp; | Clears the YouTube watch history from the browser's local storage. |
| [ConvertTo-Uris](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#convertto-uris) | &nbsp; | Parses strings for any valid URI. |
| [Copy-PDFsFromGoogleQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#copy-pdfsfromgooglequery) | &nbsp; | Downloads PDF files found through Google search results. |
| [Get-GoogleSearchResultUrls](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#get-googlesearchresulturls) | qlinksget | Performs a google search and returns the links |
| [Get-NextAffirmation](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#get-nextaffirmation) | WhatAboutIt | Returns a random affirmation text from affirmations.dev API. |
| [Get-WikipediaSummary](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#get-wikipediasummary) | wikitxt | Retrieves a summary of a topic from Wikipedia. |
| [Invoke-WebbrowserTabPollingScript](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#invoke-webbrowsertabpollingscript) | &nbsp; | Executes a background polling script in a previously selected webbrowser tab. |
| [Open-AllGoogleLinks](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-allgooglelinks) | qlinks | Performs an infinite auto opening google search . |
| [Open-AllPossibleQueries](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-allpossiblequeries) | qq | Opens all possible query types for given search terms or URLs. |
| [Open-AllPossibleTextQueries](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-allpossibletextqueries) | qqq | Executes all Text query Cmdlets in parallel and displays results. |
| [Open-AllYoutubeVideos](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-allyoutubevideos) | qvideos, qyt | Opens and controls YouTube videos in a browser window with keyboard shortcuts. |
| [Open-BingCopilotQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-bingcopilotquery) | aibc | Opens a Bing CoPilot query in a webbrowser |
| [Open-BingQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-bingquery) | bq | Opens a Bing search query in a web browser. |
| [Open-BuiltWithSiteInfo](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-builtwithsiteinfo) | &nbsp; | Opens BuiltWith website queries in a web browser. |
| [Open-ChatGPTQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-chatgptquery) | aicgpt, askchatgpt | Opens a ChatGPT query in a web browser. |
| [Open-CloudLLMChat](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-cloudllmchat) | ask | Opens a cloud LLM chat interface for AI queries. |
| [Open-DeepSearchQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-deepsearchquery) | aideepseek, askdeepsearch | Opens a DeepSeek query in a webbrowser |
| [Open-GameOfLife](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-gameoflife) | conway, gameoflife | Opens Conway's Game of Life simulation in a web browser. |
| [Open-GenXdevAppCatalog](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-genxdevappcatalog) | appcatalog | Opens the GenXdev progressive webapps catalog in a web browser. |
| [Open-GithubCopilotQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-githubcopilotquery) | aigc, askghcopilot | Opens a Github CoPilot query in a webbrowser |
| [Open-GithubQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-githubquery) | qgithub | Opens a Github repository search query in a web browser. |
| [Open-GoogleGeminiQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-googlegeminiquery) | aigg, askgemini | Opens a Google Gemini query in a webbrowser |
| [Open-GoogleQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-googlequery) | &nbsp; | &nbsp; |
| [Open-GoogleSiteInfo](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-googlesiteinfo) | &nbsp; | Opens Google site information queries in a web browser. |
| [Open-IMDBQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-imdbquery) | imdb | Opens an IMDB search query in a web browser. |
| [Open-InstantStreetViewQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-instantstreetviewquery) | isv | Opens InstantStreetView queries in a web browser. |
| [Open-MovieQuote](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-moviequote) | moviequote | Opens a video of a movie quote in a web browser. |
| [Open-SearchEngine](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-searchengine) | q | Opens a search query in the specified search engine using a web browser. |
| [Open-SimularWebSiteInfo](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-simularwebsiteinfo) | simularsite | Opens SimilarWeb website information for specified URLs in a web browser. |
| [Open-StackOverflowQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-stackoverflowquery) | qso | Opens Stack Overflow search queries in a web browser. |
| [Open-Timeline](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-timeline) | timeline | Opens an interactive timeline showing current time, date, century, and millennium. |
| [Open-ViralSimulation](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-viralsimulation) | viral | &nbsp; |
| [Open-WaybackMachineSiteInfo](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-waybackmachinesiteinfo) | wayback | Opens WaybackMachine site information in a web browser. |
| [Open-WebsiteAndPerformQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-websiteandperformquery) | owaq | Opens a webpage in a webbrowser and performs one or more queries. |
| [Open-WhoisHostSiteInfo](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-whoishostsiteinfo) | whois | Opens a Whois host information query in a web browser. |
| [Open-WikipediaNLQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-wikipedianlquery) | wikinl | Opens Dutch Wikipedia searches in a web browser. |
| [Open-WikipediaQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-wikipediaquery) | wiki | Opens a Wikipedia query in a webbrowser. |
| [Open-WolframAlphaQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-wolframalphaquery) | qalpha | Opens a Wolfram Alpha query in a web browser. |
| [Open-XGrokQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-xgrokquery) | aixg, askxgrok | Opens a X Grok query in a webbrowser |
| [Open-Yab](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-yab) | yab | Opens the YAB game in a web browser with configurable settings. |
| [Open-YabAIBattle](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-yabaibattle) | yabbattle | Opens the YabAI Battle game in a web browser. |
| [Open-YoutubeQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-youtubequery) | youtube | Opens YouTube search queries in a web browser. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Queries.AI

**A Windows PowerShell module for finding resources and information on the internet**

### Cmdlet Index

| Command | Aliases | Description |
| --- | --- | --- |
| [Clear-YoutubeWatched](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#clear-youtubewatched) | &nbsp; | Clears the YouTube watch history from the browser's local storage. |
| [ConvertTo-Uris](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#convertto-uris) | &nbsp; | Parses strings for any valid URI. |
| [Copy-PDFsFromGoogleQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#copy-pdfsfromgooglequery) | &nbsp; | Downloads PDF files found through Google search results. |
| [Get-GoogleSearchResultUrls](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#get-googlesearchresulturls) | qlinksget | Performs a google search and returns the links |
| [Get-NextAffirmation](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#get-nextaffirmation) | WhatAboutIt | Returns a random affirmation text from affirmations.dev API. |
| [Get-WikipediaSummary](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#get-wikipediasummary) | wikitxt | Retrieves a summary of a topic from Wikipedia. |
| [Invoke-WebbrowserTabPollingScript](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#invoke-webbrowsertabpollingscript) | &nbsp; | Executes a background polling script in a previously selected webbrowser tab. |
| [Open-AllGoogleLinks](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-allgooglelinks) | qlinks | Performs an infinite auto opening google search . |
| [Open-AllPossibleQueries](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-allpossiblequeries) | qq | Opens all possible query types for given search terms or URLs. |
| [Open-AllPossibleTextQueries](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-allpossibletextqueries) | qqq | Executes all Text query Cmdlets in parallel and displays results. |
| [Open-AllYoutubeVideos](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-allyoutubevideos) | qvideos, qyt | Opens and controls YouTube videos in a browser window with keyboard shortcuts. |
| [Open-BingCopilotQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-bingcopilotquery) | aibc | Opens a Bing CoPilot query in a webbrowser |
| [Open-BingQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-bingquery) | bq | Opens a Bing search query in a web browser. |
| [Open-BuiltWithSiteInfo](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-builtwithsiteinfo) | &nbsp; | Opens BuiltWith website queries in a web browser. |
| [Open-ChatGPTQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-chatgptquery) | aicgpt, askchatgpt | Opens a ChatGPT query in a web browser. |
| [Open-CloudLLMChat](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-cloudllmchat) | ask | Opens a cloud LLM chat interface for AI queries. |
| [Open-DeepSearchQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-deepsearchquery) | aideepseek, askdeepsearch | Opens a DeepSeek query in a webbrowser |
| [Open-GameOfLife](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-gameoflife) | conway, gameoflife | Opens Conway's Game of Life simulation in a web browser. |
| [Open-GenXdevAppCatalog](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-genxdevappcatalog) | appcatalog | Opens the GenXdev progressive webapps catalog in a web browser. |
| [Open-GithubCopilotQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-githubcopilotquery) | aigc, askghcopilot | Opens a Github CoPilot query in a webbrowser |
| [Open-GithubQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-githubquery) | qgithub | Opens a Github repository search query in a web browser. |
| [Open-GoogleGeminiQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-googlegeminiquery) | aigg, askgemini | Opens a Google Gemini query in a webbrowser |
| [Open-GoogleQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-googlequery) | &nbsp; | &nbsp; |
| [Open-GoogleSiteInfo](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-googlesiteinfo) | &nbsp; | Opens Google site information queries in a web browser. |
| [Open-IMDBQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-imdbquery) | imdb | Opens an IMDB search query in a web browser. |
| [Open-InstantStreetViewQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-instantstreetviewquery) | isv | Opens InstantStreetView queries in a web browser. |
| [Open-MovieQuote](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-moviequote) | moviequote | Opens a video of a movie quote in a web browser. |
| [Open-SearchEngine](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-searchengine) | q | Opens a search query in the specified search engine using a web browser. |
| [Open-SimularWebSiteInfo](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-simularwebsiteinfo) | simularsite | Opens SimilarWeb website information for specified URLs in a web browser. |
| [Open-StackOverflowQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-stackoverflowquery) | qso | Opens Stack Overflow search queries in a web browser. |
| [Open-Timeline](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-timeline) | timeline | Opens an interactive timeline showing current time, date, century, and millennium. |
| [Open-ViralSimulation](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-viralsimulation) | viral | &nbsp; |
| [Open-WaybackMachineSiteInfo](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-waybackmachinesiteinfo) | wayback | Opens WaybackMachine site information in a web browser. |
| [Open-WebsiteAndPerformQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-websiteandperformquery) | owaq | Opens a webpage in a webbrowser and performs one or more queries. |
| [Open-WhoisHostSiteInfo](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-whoishostsiteinfo) | whois | Opens a Whois host information query in a web browser. |
| [Open-WikipediaNLQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-wikipedianlquery) | wikinl | Opens Dutch Wikipedia searches in a web browser. |
| [Open-WikipediaQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-wikipediaquery) | wiki | Opens a Wikipedia query in a webbrowser. |
| [Open-WolframAlphaQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-wolframalphaquery) | qalpha | Opens a Wolfram Alpha query in a web browser. |
| [Open-XGrokQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-xgrokquery) | aixg, askxgrok | Opens a X Grok query in a webbrowser |
| [Open-Yab](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-yab) | yab | Opens the YAB game in a web browser with configurable settings. |
| [Open-YabAIBattle](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-yabaibattle) | yabbattle | Opens the YabAI Battle game in a web browser. |
| [Open-YoutubeQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-youtubequery) | youtube | Opens YouTube search queries in a web browser. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Queries.Text

**A Windows PowerShell module for finding resources and information on the internet**

### Cmdlet Index

| Command | Aliases | Description |
| --- | --- | --- |
| [Clear-YoutubeWatched](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#clear-youtubewatched) | &nbsp; | Clears the YouTube watch history from the browser's local storage. |
| [ConvertTo-Uris](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#convertto-uris) | &nbsp; | Parses strings for any valid URI. |
| [Copy-PDFsFromGoogleQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#copy-pdfsfromgooglequery) | &nbsp; | Downloads PDF files found through Google search results. |
| [Get-GoogleSearchResultUrls](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#get-googlesearchresulturls) | qlinksget | Performs a google search and returns the links |
| [Get-NextAffirmation](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#get-nextaffirmation) | WhatAboutIt | Returns a random affirmation text from affirmations.dev API. |
| [Get-WikipediaSummary](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#get-wikipediasummary) | wikitxt | Retrieves a summary of a topic from Wikipedia. |
| [Invoke-WebbrowserTabPollingScript](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#invoke-webbrowsertabpollingscript) | &nbsp; | Executes a background polling script in a previously selected webbrowser tab. |
| [Open-AllGoogleLinks](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-allgooglelinks) | qlinks | Performs an infinite auto opening google search . |
| [Open-AllPossibleQueries](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-allpossiblequeries) | qq | Opens all possible query types for given search terms or URLs. |
| [Open-AllPossibleTextQueries](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-allpossibletextqueries) | qqq | Executes all Text query Cmdlets in parallel and displays results. |
| [Open-AllYoutubeVideos](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-allyoutubevideos) | qvideos, qyt | Opens and controls YouTube videos in a browser window with keyboard shortcuts. |
| [Open-BingCopilotQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-bingcopilotquery) | aibc | Opens a Bing CoPilot query in a webbrowser |
| [Open-BingQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-bingquery) | bq | Opens a Bing search query in a web browser. |
| [Open-BuiltWithSiteInfo](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-builtwithsiteinfo) | &nbsp; | Opens BuiltWith website queries in a web browser. |
| [Open-ChatGPTQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-chatgptquery) | aicgpt, askchatgpt | Opens a ChatGPT query in a web browser. |
| [Open-CloudLLMChat](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-cloudllmchat) | ask | Opens a cloud LLM chat interface for AI queries. |
| [Open-DeepSearchQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-deepsearchquery) | aideepseek, askdeepsearch | Opens a DeepSeek query in a webbrowser |
| [Open-GameOfLife](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-gameoflife) | conway, gameoflife | Opens Conway's Game of Life simulation in a web browser. |
| [Open-GenXdevAppCatalog](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-genxdevappcatalog) | appcatalog | Opens the GenXdev progressive webapps catalog in a web browser. |
| [Open-GithubCopilotQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-githubcopilotquery) | aigc, askghcopilot | Opens a Github CoPilot query in a webbrowser |
| [Open-GithubQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-githubquery) | qgithub | Opens a Github repository search query in a web browser. |
| [Open-GoogleGeminiQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-googlegeminiquery) | aigg, askgemini | Opens a Google Gemini query in a webbrowser |
| [Open-GoogleQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-googlequery) | &nbsp; | &nbsp; |
| [Open-GoogleSiteInfo](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-googlesiteinfo) | &nbsp; | Opens Google site information queries in a web browser. |
| [Open-IMDBQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-imdbquery) | imdb | Opens an IMDB search query in a web browser. |
| [Open-InstantStreetViewQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-instantstreetviewquery) | isv | Opens InstantStreetView queries in a web browser. |
| [Open-MovieQuote](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-moviequote) | moviequote | Opens a video of a movie quote in a web browser. |
| [Open-SearchEngine](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-searchengine) | q | Opens a search query in the specified search engine using a web browser. |
| [Open-SimularWebSiteInfo](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-simularwebsiteinfo) | simularsite | Opens SimilarWeb website information for specified URLs in a web browser. |
| [Open-StackOverflowQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-stackoverflowquery) | qso | Opens Stack Overflow search queries in a web browser. |
| [Open-Timeline](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-timeline) | timeline | Opens an interactive timeline showing current time, date, century, and millennium. |
| [Open-ViralSimulation](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-viralsimulation) | viral | &nbsp; |
| [Open-WaybackMachineSiteInfo](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-waybackmachinesiteinfo) | wayback | Opens WaybackMachine site information in a web browser. |
| [Open-WebsiteAndPerformQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-websiteandperformquery) | owaq | Opens a webpage in a webbrowser and performs one or more queries. |
| [Open-WhoisHostSiteInfo](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-whoishostsiteinfo) | whois | Opens a Whois host information query in a web browser. |
| [Open-WikipediaNLQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-wikipedianlquery) | wikinl | Opens Dutch Wikipedia searches in a web browser. |
| [Open-WikipediaQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-wikipediaquery) | wiki | Opens a Wikipedia query in a webbrowser. |
| [Open-WolframAlphaQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-wolframalphaquery) | qalpha | Opens a Wolfram Alpha query in a web browser. |
| [Open-XGrokQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-xgrokquery) | aixg, askxgrok | Opens a X Grok query in a webbrowser |
| [Open-Yab](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-yab) | yab | Opens the YAB game in a web browser with configurable settings. |
| [Open-YabAIBattle](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-yabaibattle) | yabbattle | Opens the YabAI Battle game in a web browser. |
| [Open-YoutubeQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-youtubequery) | youtube | Opens YouTube search queries in a web browser. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Queries.Webbrowser

**A Windows PowerShell module for finding resources and information on the internet**

### Cmdlet Index

| Command | Aliases | Description |
| --- | --- | --- |
| [Clear-YoutubeWatched](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#clear-youtubewatched) | &nbsp; | Clears the YouTube watch history from the browser's local storage. |
| [ConvertTo-Uris](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#convertto-uris) | &nbsp; | Parses strings for any valid URI. |
| [Copy-PDFsFromGoogleQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#copy-pdfsfromgooglequery) | &nbsp; | Downloads PDF files found through Google search results. |
| [Get-GoogleSearchResultUrls](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#get-googlesearchresulturls) | qlinksget | Performs a google search and returns the links |
| [Get-NextAffirmation](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#get-nextaffirmation) | WhatAboutIt | Returns a random affirmation text from affirmations.dev API. |
| [Get-WikipediaSummary](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#get-wikipediasummary) | wikitxt | Retrieves a summary of a topic from Wikipedia. |
| [Invoke-WebbrowserTabPollingScript](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#invoke-webbrowsertabpollingscript) | &nbsp; | Executes a background polling script in a previously selected webbrowser tab. |
| [Open-AllGoogleLinks](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-allgooglelinks) | qlinks | Performs an infinite auto opening google search . |
| [Open-AllPossibleQueries](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-allpossiblequeries) | qq | Opens all possible query types for given search terms or URLs. |
| [Open-AllPossibleTextQueries](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-allpossibletextqueries) | qqq | Executes all Text query Cmdlets in parallel and displays results. |
| [Open-AllYoutubeVideos](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-allyoutubevideos) | qvideos, qyt | Opens and controls YouTube videos in a browser window with keyboard shortcuts. |
| [Open-BingCopilotQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-bingcopilotquery) | aibc | Opens a Bing CoPilot query in a webbrowser |
| [Open-BingQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-bingquery) | bq | Opens a Bing search query in a web browser. |
| [Open-BuiltWithSiteInfo](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-builtwithsiteinfo) | &nbsp; | Opens BuiltWith website queries in a web browser. |
| [Open-ChatGPTQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-chatgptquery) | aicgpt, askchatgpt | Opens a ChatGPT query in a web browser. |
| [Open-CloudLLMChat](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-cloudllmchat) | ask | Opens a cloud LLM chat interface for AI queries. |
| [Open-DeepSearchQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-deepsearchquery) | aideepseek, askdeepsearch | Opens a DeepSeek query in a webbrowser |
| [Open-GameOfLife](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-gameoflife) | conway, gameoflife | Opens Conway's Game of Life simulation in a web browser. |
| [Open-GenXdevAppCatalog](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-genxdevappcatalog) | appcatalog | Opens the GenXdev progressive webapps catalog in a web browser. |
| [Open-GithubCopilotQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-githubcopilotquery) | aigc, askghcopilot | Opens a Github CoPilot query in a webbrowser |
| [Open-GithubQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-githubquery) | qgithub | Opens a Github repository search query in a web browser. |
| [Open-GoogleGeminiQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-googlegeminiquery) | aigg, askgemini | Opens a Google Gemini query in a webbrowser |
| [Open-GoogleQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-googlequery) | &nbsp; | &nbsp; |
| [Open-GoogleSiteInfo](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-googlesiteinfo) | &nbsp; | Opens Google site information queries in a web browser. |
| [Open-IMDBQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-imdbquery) | imdb | Opens an IMDB search query in a web browser. |
| [Open-InstantStreetViewQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-instantstreetviewquery) | isv | Opens InstantStreetView queries in a web browser. |
| [Open-MovieQuote](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-moviequote) | moviequote | Opens a video of a movie quote in a web browser. |
| [Open-SearchEngine](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-searchengine) | q | Opens a search query in the specified search engine using a web browser. |
| [Open-SimularWebSiteInfo](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-simularwebsiteinfo) | simularsite | Opens SimilarWeb website information for specified URLs in a web browser. |
| [Open-StackOverflowQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-stackoverflowquery) | qso | Opens Stack Overflow search queries in a web browser. |
| [Open-Timeline](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-timeline) | timeline | Opens an interactive timeline showing current time, date, century, and millennium. |
| [Open-ViralSimulation](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-viralsimulation) | viral | &nbsp; |
| [Open-WaybackMachineSiteInfo](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-waybackmachinesiteinfo) | wayback | Opens WaybackMachine site information in a web browser. |
| [Open-WebsiteAndPerformQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-websiteandperformquery) | owaq | Opens a webpage in a webbrowser and performs one or more queries. |
| [Open-WhoisHostSiteInfo](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-whoishostsiteinfo) | whois | Opens a Whois host information query in a web browser. |
| [Open-WikipediaNLQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-wikipedianlquery) | wikinl | Opens Dutch Wikipedia searches in a web browser. |
| [Open-WikipediaQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-wikipediaquery) | wiki | Opens a Wikipedia query in a webbrowser. |
| [Open-WolframAlphaQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-wolframalphaquery) | qalpha | Opens a Wolfram Alpha query in a web browser. |
| [Open-XGrokQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-xgrokquery) | aixg, askxgrok | Opens a X Grok query in a webbrowser |
| [Open-Yab](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-yab) | yab | Opens the YAB game in a web browser with configurable settings. |
| [Open-YabAIBattle](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-yabaibattle) | yabbattle | Opens the YabAI Battle game in a web browser. |
| [Open-YoutubeQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-youtubequery) | youtube | Opens YouTube search queries in a web browser. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Queries.Websites

**A Windows PowerShell module for finding resources and information on the internet**

### Cmdlet Index

| Command | Aliases | Description |
| --- | --- | --- |
| [Clear-YoutubeWatched](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#clear-youtubewatched) | &nbsp; | Clears the YouTube watch history from the browser's local storage. |
| [ConvertTo-Uris](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#convertto-uris) | &nbsp; | Parses strings for any valid URI. |
| [Copy-PDFsFromGoogleQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#copy-pdfsfromgooglequery) | &nbsp; | Downloads PDF files found through Google search results. |
| [Get-GoogleSearchResultUrls](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#get-googlesearchresulturls) | qlinksget | Performs a google search and returns the links |
| [Get-NextAffirmation](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#get-nextaffirmation) | WhatAboutIt | Returns a random affirmation text from affirmations.dev API. |
| [Get-WikipediaSummary](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#get-wikipediasummary) | wikitxt | Retrieves a summary of a topic from Wikipedia. |
| [Invoke-WebbrowserTabPollingScript](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#invoke-webbrowsertabpollingscript) | &nbsp; | Executes a background polling script in a previously selected webbrowser tab. |
| [Open-AllGoogleLinks](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-allgooglelinks) | qlinks | Performs an infinite auto opening google search . |
| [Open-AllPossibleQueries](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-allpossiblequeries) | qq | Opens all possible query types for given search terms or URLs. |
| [Open-AllPossibleTextQueries](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-allpossibletextqueries) | qqq | Executes all Text query Cmdlets in parallel and displays results. |
| [Open-AllYoutubeVideos](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-allyoutubevideos) | qvideos, qyt | Opens and controls YouTube videos in a browser window with keyboard shortcuts. |
| [Open-BingCopilotQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-bingcopilotquery) | aibc | Opens a Bing CoPilot query in a webbrowser |
| [Open-BingQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-bingquery) | bq | Opens a Bing search query in a web browser. |
| [Open-BuiltWithSiteInfo](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-builtwithsiteinfo) | &nbsp; | Opens BuiltWith website queries in a web browser. |
| [Open-ChatGPTQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-chatgptquery) | aicgpt, askchatgpt | Opens a ChatGPT query in a web browser. |
| [Open-CloudLLMChat](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-cloudllmchat) | ask | Opens a cloud LLM chat interface for AI queries. |
| [Open-DeepSearchQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-deepsearchquery) | aideepseek, askdeepsearch | Opens a DeepSeek query in a webbrowser |
| [Open-GameOfLife](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-gameoflife) | conway, gameoflife | Opens Conway's Game of Life simulation in a web browser. |
| [Open-GenXdevAppCatalog](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-genxdevappcatalog) | appcatalog | Opens the GenXdev progressive webapps catalog in a web browser. |
| [Open-GithubCopilotQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-githubcopilotquery) | aigc, askghcopilot | Opens a Github CoPilot query in a webbrowser |
| [Open-GithubQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-githubquery) | qgithub | Opens a Github repository search query in a web browser. |
| [Open-GoogleGeminiQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-googlegeminiquery) | aigg, askgemini | Opens a Google Gemini query in a webbrowser |
| [Open-GoogleQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-googlequery) | &nbsp; | &nbsp; |
| [Open-GoogleSiteInfo](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-googlesiteinfo) | &nbsp; | Opens Google site information queries in a web browser. |
| [Open-IMDBQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-imdbquery) | imdb | Opens an IMDB search query in a web browser. |
| [Open-InstantStreetViewQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-instantstreetviewquery) | isv | Opens InstantStreetView queries in a web browser. |
| [Open-MovieQuote](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-moviequote) | moviequote | Opens a video of a movie quote in a web browser. |
| [Open-SearchEngine](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-searchengine) | q | Opens a search query in the specified search engine using a web browser. |
| [Open-SimularWebSiteInfo](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-simularwebsiteinfo) | simularsite | Opens SimilarWeb website information for specified URLs in a web browser. |
| [Open-StackOverflowQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-stackoverflowquery) | qso | Opens Stack Overflow search queries in a web browser. |
| [Open-Timeline](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-timeline) | timeline | Opens an interactive timeline showing current time, date, century, and millennium. |
| [Open-ViralSimulation](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-viralsimulation) | viral | &nbsp; |
| [Open-WaybackMachineSiteInfo](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-waybackmachinesiteinfo) | wayback | Opens WaybackMachine site information in a web browser. |
| [Open-WebsiteAndPerformQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-websiteandperformquery) | owaq | Opens a webpage in a webbrowser and performs one or more queries. |
| [Open-WhoisHostSiteInfo](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-whoishostsiteinfo) | whois | Opens a Whois host information query in a web browser. |
| [Open-WikipediaNLQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-wikipedianlquery) | wikinl | Opens Dutch Wikipedia searches in a web browser. |
| [Open-WikipediaQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-wikipediaquery) | wiki | Opens a Wikipedia query in a webbrowser. |
| [Open-WolframAlphaQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-wolframalphaquery) | qalpha | Opens a Wolfram Alpha query in a web browser. |
| [Open-XGrokQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-xgrokquery) | aixg, askxgrok | Opens a X Grok query in a webbrowser |
| [Open-Yab](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-yab) | yab | Opens the YAB game in a web browser with configurable settings. |
| [Open-YabAIBattle](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-yabaibattle) | yabbattle | Opens the YabAI Battle game in a web browser. |
| [Open-YoutubeQuery](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md#open-youtubequery) | youtube | Opens YouTube search queries in a web browser. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Webbrowser

**PowerShell module for webbrowser operations**

### Cmdlet Index

| Command | Aliases | Description |
| --- | --- | --- |
| [Approve-FirefoxDebugging](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#approve-firefoxdebugging) | &nbsp; | Configures Firefox's debugging and standalone app mode features. |
| [Clear-WebbrowserTabSiteApplicationData](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#clear-webbrowsertabsiteapplicationdata) | clearsitedata | Clears all browser storage data for the current tab in Edge or Chrome. |
| [Close-Webbrowser](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#close-webbrowser) | wbc | Closes one or more webbrowser instances selectively. |
| [Close-WebbrowserTab](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#close-webbrowsertab) | CloseTab, ct | Closes the currently selected webbrowser tab. |
| [Connect-PlaywrightViaDebuggingPort](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#connect-playwrightviadebuggingport) | &nbsp; | Connects to an existing browser instance via debugging port. |
| [Export-BrowserBookmarks](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#export-browserbookmarks) | &nbsp; | Exports browser bookmarks to a JSON file. |
| [Find-BrowserBookmark](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#find-browserbookmark) | bookmarks | Finds bookmarks from one or more web browsers. |
| [Get-BrowserBookmark](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#get-browserbookmark) | gbm | Returns all bookmarks from installed web browsers. |
| [Get-ChromeRemoteDebuggingPort](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#get-chromeremotedebuggingport) | Get-ChromePort | Returns the configured remote debugging port for Google Chrome. |
| [Get-ChromiumRemoteDebuggingPort](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#get-chromiumremotedebuggingport) | Get-BrowserDebugPort | Returns the remote debugging port for the system's default Chromium browser. |
| [Get-ChromiumSessionReference](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#get-chromiumsessionreference) | &nbsp; | Gets a serializable reference to the current browser tab session. |
| [Get-DefaultWebbrowser](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#get-defaultwebbrowser) | &nbsp; | Returns the configured default web browser for the current user. |
| [Get-EdgeRemoteDebuggingPort](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#get-edgeremotedebuggingport) | &nbsp; | Returns the configured remote debugging port for Microsoft Edge browser. |
| [Get-PlaywrightProfileDirectory](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#get-playwrightprofiledirectory) | &nbsp; | Gets the Playwright browser profile directory for persistent sessions. |
| [Get-Webbrowser](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#get-webbrowser) | &nbsp; | Returns a collection of installed modern web browsers. |
| [Get-WebbrowserTabDomNodes](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#get-webbrowsertabdomnodes) | wl | Queries and manipulates DOM nodes in the active browser tab using CSS selectors. |
| [Import-BrowserBookmarks](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#import-browserbookmarks) | &nbsp; | Imports bookmarks from a file or collection into a web browser. |
| [Invoke-WebbrowserEvaluation](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#invoke-webbrowserevaluation) | et, Eval | Executes JavaScript code in a selected web browser tab. |
| [Open-BrowserBookmarks](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#open-browserbookmarks) | sites | Opens browser bookmarks that match specified search criteria. |
| [Open-Webbrowser](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#open-webbrowser) | wb | Opens URLs in one or more browser windows with optional positioning and styling. |
| [Resume-WebbrowserTabVideo](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#resume-webbrowsertabvideo) | wbvideoplay | Resumes video playback in a YouTube browser tab. |
| [Select-WebbrowserTab](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#select-webbrowsertab) | Select-BrowserTab, st | Selects a browser tab for automation in Chrome or Edge. |
| [Set-BrowserVideoFullscreen](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#set-browservideofullscreen) | fsvideo | Maximizes the first video element found in the current browser tab. |
| [Set-RemoteDebuggerPortInBrowserShortcuts](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#set-remotedebuggerportinbrowsershortcuts) | &nbsp; | Updates browser shortcuts to enable remote debugging ports. |
| [Set-WebbrowserTabLocation](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#set-webbrowsertablocation) | lt, Nav | Navigates the current webbrowser tab to a specified URL. |
| [Show-WebsiteInAllBrowsers](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#show-websiteinallbrowsers) | Show-UrlInAllBrowsers | Opens a URL in multiple browsers simultaneously in a mosaic layout. |
| [Stop-WebbrowserVideos](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#stop-webbrowservideos) | ssst, wbsst, wbvideostop | Pauses video playback in all active browser sessions. |
| [Unprotect-WebbrowserTab](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#unprotect-webbrowsertab) | wbctrl | Takes control of a selected web browser tab for interactive manipulation. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Webbrowser.Playwright

**PowerShell module for webbrowser.playwright operations**

### Cmdlet Index

| Command | Aliases | Description |
| --- | --- | --- |
| [Approve-FirefoxDebugging](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#approve-firefoxdebugging) | &nbsp; | Configures Firefox's debugging and standalone app mode features. |
| [Clear-WebbrowserTabSiteApplicationData](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#clear-webbrowsertabsiteapplicationdata) | clearsitedata | Clears all browser storage data for the current tab in Edge or Chrome. |
| [Close-Webbrowser](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#close-webbrowser) | wbc | Closes one or more webbrowser instances selectively. |
| [Close-WebbrowserTab](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#close-webbrowsertab) | CloseTab, ct | Closes the currently selected webbrowser tab. |
| [Connect-PlaywrightViaDebuggingPort](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#connect-playwrightviadebuggingport) | &nbsp; | Connects to an existing browser instance via debugging port. |
| [Export-BrowserBookmarks](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#export-browserbookmarks) | &nbsp; | Exports browser bookmarks to a JSON file. |
| [Find-BrowserBookmark](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#find-browserbookmark) | bookmarks | Finds bookmarks from one or more web browsers. |
| [Get-BrowserBookmark](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#get-browserbookmark) | gbm | Returns all bookmarks from installed web browsers. |
| [Get-ChromeRemoteDebuggingPort](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#get-chromeremotedebuggingport) | Get-ChromePort | Returns the configured remote debugging port for Google Chrome. |
| [Get-ChromiumRemoteDebuggingPort](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#get-chromiumremotedebuggingport) | Get-BrowserDebugPort | Returns the remote debugging port for the system's default Chromium browser. |
| [Get-ChromiumSessionReference](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#get-chromiumsessionreference) | &nbsp; | Gets a serializable reference to the current browser tab session. |
| [Get-DefaultWebbrowser](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#get-defaultwebbrowser) | &nbsp; | Returns the configured default web browser for the current user. |
| [Get-EdgeRemoteDebuggingPort](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#get-edgeremotedebuggingport) | &nbsp; | Returns the configured remote debugging port for Microsoft Edge browser. |
| [Get-PlaywrightProfileDirectory](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#get-playwrightprofiledirectory) | &nbsp; | Gets the Playwright browser profile directory for persistent sessions. |
| [Get-Webbrowser](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#get-webbrowser) | &nbsp; | Returns a collection of installed modern web browsers. |
| [Get-WebbrowserTabDomNodes](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#get-webbrowsertabdomnodes) | wl | Queries and manipulates DOM nodes in the active browser tab using CSS selectors. |
| [Import-BrowserBookmarks](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#import-browserbookmarks) | &nbsp; | Imports bookmarks from a file or collection into a web browser. |
| [Invoke-WebbrowserEvaluation](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#invoke-webbrowserevaluation) | et, Eval | Executes JavaScript code in a selected web browser tab. |
| [Open-BrowserBookmarks](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#open-browserbookmarks) | sites | Opens browser bookmarks that match specified search criteria. |
| [Open-Webbrowser](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#open-webbrowser) | wb | Opens URLs in one or more browser windows with optional positioning and styling. |
| [Resume-WebbrowserTabVideo](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#resume-webbrowsertabvideo) | wbvideoplay | Resumes video playback in a YouTube browser tab. |
| [Select-WebbrowserTab](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#select-webbrowsertab) | Select-BrowserTab, st | Selects a browser tab for automation in Chrome or Edge. |
| [Set-BrowserVideoFullscreen](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#set-browservideofullscreen) | fsvideo | Maximizes the first video element found in the current browser tab. |
| [Set-RemoteDebuggerPortInBrowserShortcuts](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#set-remotedebuggerportinbrowsershortcuts) | &nbsp; | Updates browser shortcuts to enable remote debugging ports. |
| [Set-WebbrowserTabLocation](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#set-webbrowsertablocation) | lt, Nav | Navigates the current webbrowser tab to a specified URL. |
| [Show-WebsiteInAllBrowsers](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#show-websiteinallbrowsers) | Show-UrlInAllBrowsers | Opens a URL in multiple browsers simultaneously in a mosaic layout. |
| [Stop-WebbrowserVideos](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#stop-webbrowservideos) | ssst, wbsst, wbvideostop | Pauses video playback in all active browser sessions. |
| [Unprotect-WebbrowserTab](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md#unprotect-webbrowsertab) | wbctrl | Takes control of a selected web browser tab for interactive manipulation. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Windows

**PowerShell module for windows operations**

### Cmdlet Index

| Command | Aliases | Description |
| --- | --- | --- |
| [Add-WireGuardPeer](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#add-wireguardpeer) | &nbsp; | Adds a new WireGuard VPN peer (client) configuration to the server. |
| [CurrentUserHasElevatedRights](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#currentuserhaselevatedrights) | &nbsp; | Checks if the current user has elevated rights. |
| [EnsureDockerDesktop](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#ensuredockerdesktop) | &nbsp; | Checks if the WinGet PowerShell module is installed. |
| [EnsurePSTools](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#ensurepstools) | &nbsp; | Ensures Sysinternals tools (PSTools) are installed and available. |
| [EnsureWireGuard](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#ensurewireguard) | &nbsp; | Ensures WireGuard VPN service is installed and running via Docker container. |
| [Get-ActiveUser](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#get-activeuser) | gusers | Retrieves a list of unique usernames from currently active system processes. |
| [Get-ChildProcesses](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#get-childprocesses) | &nbsp; | Retrieves all processes that are descendants of the current PowerShell process. |
| [Get-ClipboardFiles](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#get-clipboardfiles) | getclipfiles | Gets files from the Windows clipboard that were set for file operations like copy/paste. |
| [Get-CurrentFocusedProcess](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#get-currentfocusedprocess) | &nbsp; | Retrieves the process object of the window that currently has keyboard focus. |
| [Get-DesktopScalingFactor](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#get-desktopscalingfactor) | &nbsp; | Retrieves the Windows display scaling factor (DPI setting) for a specified monitor. |
| [Get-ForegroundWindow](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#get-foregroundwindow) | &nbsp; | Gets the handle of the currently active foreground window. |
| [Get-KnownFolderPath](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#get-knownfolderpath) | folder | Gets the path of a Windows known folder using the Windows Shell32 API. |
| [Get-MonitorCount](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#get-monitorcount) | &nbsp; | Gets the total number of display monitors connected to the system. |
| [Get-MpCmdRunPath](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#get-mpcmdrunpath) | &nbsp; | Gets the path to the Windows Defender MpCmdRun.exe executable. |
| [Get-OpenedFileHandleProcesses](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#get-openedfilehandleprocesses) | &nbsp; | Retrieves processes that have open file handles to specified files. |
| [Get-PowershellMainWindow](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#get-powershellmainwindow) | &nbsp; | Returns a window helper object for the PowerShell terminal's main window. |
| [Get-PowershellMainWindowProcess](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#get-powershellmainwindowprocess) | &nbsp; | Returns the process object for the window hosting the PowerShell terminal. |
| [Get-Window](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#get-window) | gwin, window | Gets window information for specified processes or window handles. |
| [Get-WireGuardPeerQRCode](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#get-wireguardpeerqrcode) | &nbsp; | Generates a QR code for a WireGuard VPN peer configuration. |
| [Get-WireGuardPeers](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#get-wireguardpeers) | &nbsp; | Gets information about all WireGuard VPN peers configured on the system. |
| [Get-WireGuardStatus](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#get-wireguardstatus) | &nbsp; | Gets detailed status information about the WireGuard VPN server. |
| [Initialize-ScheduledTaskScripts](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#initialize-scheduledtaskscripts) | &nbsp; | Creates scheduled tasks that run PowerShell scripts at specified intervals. |
| [Invoke-WindowsUpdate](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#invoke-windowsupdate) | Get-WindowsIsUpToDate, updatewindows | Checks if Windows is up to date and optionally installs available updates. |
| [Pop-Window](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#pop-window) | popw | Pops the last active window helper from the stack with optional modifications. |
| [Push-Window](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#push-window) | pushw | Pushes the current window onto the window stack with optional modifications. |
| [Remove-WireGuardPeer](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#remove-wireguardpeer) | &nbsp; | Removes a WireGuard VPN peer configuration. |
| [Reset-WireGuardConfiguration](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#reset-wireguardconfiguration) | &nbsp; | Resets the WireGuard VPN server configuration, removing all peers. |
| [Send-Key](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#send-key) | invokekeys, sendkeys | Sends simulated keystrokes to a window or process. |
| [Set-ClipboardFiles](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#set-clipboardfiles) | setclipfiles | Sets files to the Windows clipboard for file operations like copy/paste. |
| [Set-ForegroundWindow](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#set-foregroundwindow) | &nbsp; | Brings the specified window to the foreground and makes it the active window. |
| [Set-KnownFolderPath](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#set-knownfolderpath) | &nbsp; | Modifies the physical path of a Windows known folder. |
| [Set-TaskbarAlignment](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#set-taskbaralignment) | Set-TaskAlign | Configures Windows 11+ taskbar alignment between center and left positions. |
| [Set-WindowPosition](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#set-windowposition) | wp | Positions and resizes windows when explicit positioning parameters are provided. |
| [Set-WindowPositionForSecondary](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#set-windowpositionforsecondary) | wps | Positions a window on the secondary monitor with specified layout options. |
| [Set-WindowsWallpaper](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#set-windowswallpaper) | setaswallpaper | Sets a random wallpaper from a specified directory. |
| [Start-ProcessWithPriority](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#start-processwithpriority) | nice | Starts a process with a specified priority level. |
| [Test-PathUsingWindowsDefender](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#test-pathusingwindowsdefender) | HasNoVirus, virusscan | Scans files or directories for malware using Windows Defender. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Windows.WireGuard

**PowerShell module for windows.wireguard operations**

### Cmdlet Index

| Command | Aliases | Description |
| --- | --- | --- |
| [Add-WireGuardPeer](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#add-wireguardpeer) | &nbsp; | Adds a new WireGuard VPN peer (client) configuration to the server. |
| [CurrentUserHasElevatedRights](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#currentuserhaselevatedrights) | &nbsp; | Checks if the current user has elevated rights. |
| [EnsureDockerDesktop](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#ensuredockerdesktop) | &nbsp; | Checks if the WinGet PowerShell module is installed. |
| [EnsurePSTools](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#ensurepstools) | &nbsp; | Ensures Sysinternals tools (PSTools) are installed and available. |
| [EnsureWireGuard](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#ensurewireguard) | &nbsp; | Ensures WireGuard VPN service is installed and running via Docker container. |
| [Get-ActiveUser](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#get-activeuser) | gusers | Retrieves a list of unique usernames from currently active system processes. |
| [Get-ChildProcesses](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#get-childprocesses) | &nbsp; | Retrieves all processes that are descendants of the current PowerShell process. |
| [Get-ClipboardFiles](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#get-clipboardfiles) | getclipfiles | Gets files from the Windows clipboard that were set for file operations like copy/paste. |
| [Get-CurrentFocusedProcess](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#get-currentfocusedprocess) | &nbsp; | Retrieves the process object of the window that currently has keyboard focus. |
| [Get-DesktopScalingFactor](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#get-desktopscalingfactor) | &nbsp; | Retrieves the Windows display scaling factor (DPI setting) for a specified monitor. |
| [Get-ForegroundWindow](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#get-foregroundwindow) | &nbsp; | Gets the handle of the currently active foreground window. |
| [Get-KnownFolderPath](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#get-knownfolderpath) | folder | Gets the path of a Windows known folder using the Windows Shell32 API. |
| [Get-MonitorCount](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#get-monitorcount) | &nbsp; | Gets the total number of display monitors connected to the system. |
| [Get-MpCmdRunPath](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#get-mpcmdrunpath) | &nbsp; | Gets the path to the Windows Defender MpCmdRun.exe executable. |
| [Get-OpenedFileHandleProcesses](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#get-openedfilehandleprocesses) | &nbsp; | Retrieves processes that have open file handles to specified files. |
| [Get-PowershellMainWindow](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#get-powershellmainwindow) | &nbsp; | Returns a window helper object for the PowerShell terminal's main window. |
| [Get-PowershellMainWindowProcess](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#get-powershellmainwindowprocess) | &nbsp; | Returns the process object for the window hosting the PowerShell terminal. |
| [Get-Window](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#get-window) | gwin, window | Gets window information for specified processes or window handles. |
| [Get-WireGuardPeerQRCode](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#get-wireguardpeerqrcode) | &nbsp; | Generates a QR code for a WireGuard VPN peer configuration. |
| [Get-WireGuardPeers](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#get-wireguardpeers) | &nbsp; | Gets information about all WireGuard VPN peers configured on the system. |
| [Get-WireGuardStatus](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#get-wireguardstatus) | &nbsp; | Gets detailed status information about the WireGuard VPN server. |
| [Initialize-ScheduledTaskScripts](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#initialize-scheduledtaskscripts) | &nbsp; | Creates scheduled tasks that run PowerShell scripts at specified intervals. |
| [Invoke-WindowsUpdate](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#invoke-windowsupdate) | Get-WindowsIsUpToDate, updatewindows | Checks if Windows is up to date and optionally installs available updates. |
| [Pop-Window](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#pop-window) | popw | Pops the last active window helper from the stack with optional modifications. |
| [Push-Window](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#push-window) | pushw | Pushes the current window onto the window stack with optional modifications. |
| [Remove-WireGuardPeer](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#remove-wireguardpeer) | &nbsp; | Removes a WireGuard VPN peer configuration. |
| [Reset-WireGuardConfiguration](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#reset-wireguardconfiguration) | &nbsp; | Resets the WireGuard VPN server configuration, removing all peers. |
| [Send-Key](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#send-key) | invokekeys, sendkeys | Sends simulated keystrokes to a window or process. |
| [Set-ClipboardFiles](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#set-clipboardfiles) | setclipfiles | Sets files to the Windows clipboard for file operations like copy/paste. |
| [Set-ForegroundWindow](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#set-foregroundwindow) | &nbsp; | Brings the specified window to the foreground and makes it the active window. |
| [Set-KnownFolderPath](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#set-knownfolderpath) | &nbsp; | Modifies the physical path of a Windows known folder. |
| [Set-TaskbarAlignment](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#set-taskbaralignment) | Set-TaskAlign | Configures Windows 11+ taskbar alignment between center and left positions. |
| [Set-WindowPosition](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#set-windowposition) | wp | Positions and resizes windows when explicit positioning parameters are provided. |
| [Set-WindowPositionForSecondary](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#set-windowpositionforsecondary) | wps | Positions a window on the secondary monitor with specified layout options. |
| [Set-WindowsWallpaper](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#set-windowswallpaper) | setaswallpaper | Sets a random wallpaper from a specified directory. |
| [Start-ProcessWithPriority](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#start-processwithpriority) | nice | Starts a process with a specified priority level. |
| [Test-PathUsingWindowsDefender](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md#test-pathusingwindowsdefender) | HasNoVirus, virusscan | Scans files or directories for malware using Windows Defender. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

