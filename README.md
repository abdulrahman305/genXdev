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
| :--- | :--- | :--- |
| [GenXdev.AI](#genxdevai) | A Windows PowerShell module for local AI related operations | [📁 GenXdev.AI](https://github.com/genXdev/GenXdev.AI) |
| [GenXdev.Coding](#genxdevcoding) | A Windows PowerShell module that helps being more productive with coding tasks. | [📁 GenXdev.Coding](https://github.com/genXdev/GenXdev.Coding) |
| [GenXdev.Console](#genxdevconsole) | A Windows PowerShell module for enhancing the commandline experience | [📁 GenXdev.Console](https://github.com/genXdev/GenXdev.Console) |
| [GenXdev.Data](#genxdevdata) | A Windows PowerShell module for enhancing the commandline experience | [📁 GenXdev.Data](https://github.com/genXdev/GenXdev.Data) |
| [GenXdev.FileSystem](#genxdevfilesystem) | A Windows PowerShell module for basic and advanced file management tasks | [📁 GenXdev.FileSystem](https://github.com/genXdev/GenXdev.FileSystem) |
| [GenXdev.Helpers](#genxdevhelpers) | A Windows PowerShell module with helpers mostly used by other GenXdev modules | [📁 GenXdev.Helpers](https://github.com/genXdev/GenXdev.Helpers) |
| [GenXdev.Media](#genxdevmedia) | A Windows PowerShell module that helps with converting media files like pictures and video files | [📁 GenXdev.Media](https://github.com/genXdev/GenXdev.Media) |
| [GenXdev.Queries](#genxdevqueries) | A Windows PowerShell module for finding resources and information on the internet | [📁 GenXdev.Queries](https://github.com/genXdev/GenXdev.Queries) |
| [GenXdev.Webbrowser](#genxdevwebbrowser) | A Windows PowerShell module for webbrowser operations | [📁 GenXdev.Webbrowser](https://github.com/genXdev/GenXdev.Webbrowser) |
| [GenXdev.Windows](#genxdevwindows) | A Windows PowerShell module for windows operations | [📁 GenXdev.Windows](https://github.com/genXdev/GenXdev.Windows) |

<br/><hr/><br/>

## GenXdev.AI

**A Windows PowerShell module for local AI related operations**

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [Add-EmoticonsToText](https://github.com/genXdev/GenXdev.AI/tree/main#add-emoticonstotext) | emojify | Enhances text by adding contextually appropriate emoticons using AI. |
| [Add-GenXdevMCPServerToLMStudio](https://github.com/genXdev/GenXdev.AI/tree/main#add-genxdevmcpservertolmstudio) | &nbsp; | Adds the GenXdev MCP server to LM Studio using a deeplink configuration. |
| [Add-ImageDirectories](https://github.com/genXdev/GenXdev.AI/tree/main#add-imagedirectories) | addimgdir | Adds directories to the configured image directories for GenXdev.AI operations. |
| [Approve-NewTextFileContent](https://github.com/genXdev/GenXdev.AI/tree/main#approve-newtextfilecontent) | &nbsp; | Interactive file content comparison and approval using WinMerge. |
| [Compare-ImageFaces](https://github.com/genXdev/GenXdev.AI/tree/main#compare-imagefaces) | comparefaces | Processes the face match result from DeepStack API. |
| [Convert-DotNetTypeToLLMType](https://github.com/genXdev/GenXdev.AI/tree/main#convert-dotnettypetollmtype) | &nbsp; | Converts .NET type names to LLM (Language Model) type names. |
| [ConvertComfyImageFormat](https://github.com/genXdev/GenXdev.AI/tree/main#convertcomfyimageformat) | &nbsp; | Converts image file format while preserving maximum quality. |
| [ConvertFrom-CorporateSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertfrom-corporatespeak) | uncorporatize | Converts polite, professional corporate speak into direct, clear language using AI. |
| [ConvertFrom-DiplomaticSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertfrom-diplomaticspeak) | undiplomatize | &nbsp; |
| [ConvertTo-CorporateSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertto-corporatespeak) | corporatize | Converts direct or blunt text into polite, professional corporate speak using AI. |
| [ConvertTo-DiplomaticSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertto-diplomaticspeak) | diplomatize | Converts direct or blunt text into polite, tactful diplomatic language. |
| [ConvertTo-LMStudioFunctionDefinition](https://github.com/genXdev/GenXdev.AI/tree/main#convertto-lmstudiofunctiondefinition) | &nbsp; | Converts PowerShell functions to LMStudio function definitions. |
| [CreateComfySDXLWorkflow](https://github.com/genXdev/GenXdev.AI/tree/main#createcomfysdxlworkflow) | &nbsp; | Creates comprehensive ComfyUI SDXL workflow configuration supporting all parameters |
| [CreateComfyUniversalWorkflow](https://github.com/genXdev/GenXdev.AI/tree/main#createcomfyuniversalworkflow) | &nbsp; | Creates comprehensive ComfyUI workflow configuration supporting all parameters |
| [DownloadComfyResults](https://github.com/genXdev/GenXdev.AI/tree/main#downloadcomfyresults) | &nbsp; | Downloads generated results from ComfyUI server with file information |
| [EnsureComfyUI](https://github.com/genXdev/GenXdev.AI/tree/main#ensurecomfyui) | &nbsp; | Ensures ComfyUI is installed and running with optional window positioning. |
| [EnsureComfyUIModel](https://github.com/genXdev/GenXdev.AI/tree/main#ensurecomfyuimodel) | &nbsp; | Ensures specified ComfyUI models are available locally with automatic download |
| [EnsureDeepStack](https://github.com/genXdev/GenXdev.AI/tree/main#ensuredeepstack) | &nbsp; | Ensures DeepStack face recognition service is installed and running. |
| [EnsureGithubCLIInstalled](https://github.com/genXdev/GenXdev.AI/tree/main#ensuregithubcliinstalled) | &nbsp; | Ensures GitHub CLI is properly installed and configured on the system. |
| [EnsureHuggingFace](https://github.com/genXdev/GenXdev.AI/tree/main#ensurehuggingface) | &nbsp; | Ensures the Hugging Face CLI is installed and functional. |
| [EnsureLMStudio](https://github.com/genXdev/GenXdev.AI/tree/main#ensurelmstudio) | &nbsp; | Ensures LM Studio is properly initialized with the specified model. |
| [EnsurePaintNet](https://github.com/genXdev/GenXdev.AI/tree/main#ensurepaintnet) | &nbsp; | Ensures Paint.NET is properly installed and accessible on the system. |
| [EnsurePip](https://github.com/genXdev/GenXdev.AI/tree/main#ensurepip) | &nbsp; | Ensures pip is installed and functional for the specified Python installation. |
| [EnsurePython](https://github.com/genXdev/GenXdev.AI/tree/main#ensurepython) | &nbsp; | Ensures Python is installed and available in the system PATH. |
| [EnsureWinMergeInstalled](https://github.com/genXdev/GenXdev.AI/tree/main#ensurewinmergeinstalled) | &nbsp; | Ensures WinMerge is installed and available for file comparison operations. |
| [Export-ImageIndex](https://github.com/genXdev/GenXdev.AI/tree/main#export-imageindex) | indeximages | Initializes and populates the SQLite database by discovering images directly. |
| [Find-Image](https://github.com/genXdev/GenXdev.AI/tree/main#find-image) | findimages, li | &nbsp; |
| [Find-IndexedImage](https://github.com/genXdev/GenXdev.AI/tree/main#find-indexedimage) | findindexedimages, lii | Searches for images using an optimized SQLite database with fast indexed lookups. |
| [GenerateMasonryLayoutHtml](https://github.com/genXdev/GenXdev.AI/tree/main#generatemasonrylayouthtml) | &nbsp; | Generates a responsive masonry layout HTML gallery from image data. |
| [Get-AIDefaultLLMSettings](https://github.com/genXdev/GenXdev.AI/tree/main#get-aidefaultllmsettings) | &nbsp; | Gets all available default LLM settings configurations for AI operations in GenXdev.AI. |
| [Get-AIImageCollection](https://github.com/genXdev/GenXdev.AI/tree/main#get-aiimagecollection) | getimgdirs | Gets the configured directories for image files used in GenXdev.AI operations. |
| [Get-AIKnownFacesRootpath](https://github.com/genXdev/GenXdev.AI/tree/main#get-aiknownfacesrootpath) | &nbsp; | &nbsp; |
| [Get-AILLMSettings](https://github.com/genXdev/GenXdev.AI/tree/main#get-aillmsettings) | &nbsp; | Gets the LLM settings for AI operations in GenXdev.AI. |
| [Get-AIMetaLanguage](https://github.com/genXdev/GenXdev.AI/tree/main#get-aimetalanguage) | getimgmetalang | Gets the configured default language for image metadata operations. |
| [Get-ComfyUIModelPath](https://github.com/genXdev/GenXdev.AI/tree/main#get-comfyuimodelpath) | &nbsp; | Gets the correct ComfyUI models directory path for the current installation |
| [Get-CpuCore](https://github.com/genXdev/GenXdev.AI/tree/main#get-cpucore) | &nbsp; | Calculates and returns the total number of logical CPU cores in the system. |
| [Get-Fallacy](https://github.com/genXdev/GenXdev.AI/tree/main#get-fallacy) | dispicetext | Analyzes text to identify logical fallacies using AI-powered detection. |
| [Get-HasCapableGpu](https://github.com/genXdev/GenXdev.AI/tree/main#get-hascapablegpu) | &nbsp; | Determines if a CUDA-capable GPU with sufficient memory is present. |
| [Get-ImageDetectedFaces](https://github.com/genXdev/GenXdev.AI/tree/main#get-imagedetectedfaces) | &nbsp; | &nbsp; |
| [Get-ImageDetectedObjects](https://github.com/genXdev/GenXdev.AI/tree/main#get-imagedetectedobjects) | &nbsp; | Detects and classifies objects in an uploaded image using DeepStack. |
| [Get-ImageDetectedScenes](https://github.com/genXdev/GenXdev.AI/tree/main#get-imagedetectedscenes) | &nbsp; | Classifies an image into one of 365 scene categories using DeepStack. |
| [Get-ImageIndexPath](https://github.com/genXdev/GenXdev.AI/tree/main#get-imageindexpath) | &nbsp; | Returns the path to the image database, initializing or rebuilding it if needed. |
| [Get-ImageIndexStats](https://github.com/genXdev/GenXdev.AI/tree/main#get-imageindexstats) | getimagedbstats, gids | Retrieves comprehensive statistics and information about the image database. |
| [Get-LMStudioLoadedModelList](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudioloadedmodellist) | &nbsp; | Retrieves the list of currently loaded models from LM Studio. |
| [Get-LMStudioModelList](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiomodellist) | &nbsp; | Retrieves a list of installed LM Studio models. |
| [Get-LMStudioPaths](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiopaths) | &nbsp; | Retrieves file paths for LM Studio executables. |
| [Get-LMStudioTextEmbedding](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiotextembedding) | &nbsp; | Gets text embeddings from LM Studio model. |
| [Get-LMStudioWindow](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiowindow) | lmstudiowindow, setlmstudiowindow | Gets a window helper for the LM Studio application. |
| [Get-NumberOfCpuCores](https://github.com/genXdev/GenXdev.AI/tree/main#get-numberofcpucores) | &nbsp; | Calculates and returns the total number of logical CPU cores in the system. |
| [Get-RegisteredFaces](https://github.com/genXdev/GenXdev.AI/tree/main#get-registeredfaces) | &nbsp; | Retrieves a list of all registered face identifiers from DeepStack. |
| [Get-ScriptExecutionErrorFixPrompt](https://github.com/genXdev/GenXdev.AI/tree/main#get-scriptexecutionerrorfixprompt) | getfixprompt | Captures error messages from various streams and uses LLM to suggest fixes. |
| [Get-SimularMovieTitles](https://github.com/genXdev/GenXdev.AI/tree/main#get-simularmovietitles) | &nbsp; | Finds similar movie titles based on common properties. |
| [Get-TextTranslation](https://github.com/genXdev/GenXdev.AI/tree/main#get-texttranslation) | translate | Translates text to another language using AI. |
| [Get-VectorSimilarity](https://github.com/genXdev/GenXdev.AI/tree/main#get-vectorsimilarity) | &nbsp; | &nbsp; |
| [Initialize-LMStudioModel](https://github.com/genXdev/GenXdev.AI/tree/main#initialize-lmstudiomodel) | initlmstudio | Initializes and loads an AI model in LM Studio. |
| [Install-LMStudioApplication](https://github.com/genXdev/GenXdev.AI/tree/main#install-lmstudioapplication) | &nbsp; | Installs LM Studio application using WinGet package manager. |
| [Invoke-AIPowershellCommand](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-aipowershellcommand) | hint | Converts AI command suggestions to JSON format for processing. |
| [Invoke-ComfyUIImageGeneration](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-comfyuiimagegeneration) | generateimage | &nbsp; |
| [Invoke-CommandFromToolCall](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-commandfromtoolcall) | &nbsp; | Executes a tool call function with validation and parameter filtering. |
| [Invoke-HuggingFaceCli](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-huggingfacecli) | &nbsp; | Invokes the Hugging Face CLI with the specified arguments. |
| [Invoke-ImageEnhancement](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imageenhancement) | enhanceimage | Enhances an image by enlarging it 4X while improving quality using DeepStack. |
| [Invoke-ImageFacesUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagefacesupdate) | imagepeopledetection | Updates face recognition metadata for image files in a specified directory. |
| [Invoke-ImageKeywordUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagekeywordupdate) | imagekeywordgeneration | Updates image metadata with AI-generated descriptions and keywords. |
| [Invoke-ImageMetadataUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagemetadataupdate) | imagepropdetection | Updates EXIF metadata for images in a directory. |
| [Invoke-ImageObjectsUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imageobjectsupdate) | imageobjectdetection | Updates object detection metadata for image files in a specified directory. |
| [Invoke-ImageScenesUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagescenesupdate) | imagescenedetection | Updates scene classification metadata for image files in a specified directory. |
| [Invoke-LLMBooleanEvaluation](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmbooleanevaluation) | equalstrue | Evaluates a statement using AI to determine if it's true or false. |
| [Invoke-LLMQuery](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmquery) | llm, qllm | &nbsp; |
| [Invoke-LLMStringListEvaluation](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmstringlistevaluation) | getlist, getstring | &nbsp; |
| [Invoke-LLMTextTransformation](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmtexttransformation) | spellcheck | Transforms text using AI-powered processing. |
| [Invoke-QueryImageContent](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-queryimagecontent) | &nbsp; | Analyzes image content using AI vision capabilities through the LM-Studio API. |
| [Invoke-WinMerge](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-winmerge) | &nbsp; | Launches WinMerge to compare two files side by side. |
| [New-LLMAudioChat](https://github.com/genXdev/GenXdev.AI/tree/main#new-llmaudiochat) | llmaudiochat | Creates an interactive audio chat session with an LLM model. |
| [New-LLMTextChat](https://github.com/genXdev/GenXdev.AI/tree/main#new-llmtextchat) | llmchat | Starts an interactive text chat session with AI capabilities. |
| [QueueComfyWorkflow](https://github.com/genXdev/GenXdev.AI/tree/main#queuecomfyworkflow) | &nbsp; | Submits workflow to ComfyUI processing queue for execution. |
| [Register-AllFaces](https://github.com/genXdev/GenXdev.AI/tree/main#register-allfaces) | UpdateFaces | Updates all face recognition profiles from image files in the faces directory. |
| [Register-Face](https://github.com/genXdev/GenXdev.AI/tree/main#register-face) | &nbsp; | Registers a new face with the DeepStack face recognition API. |
| [Remove-ImageDirectories](https://github.com/genXdev/GenXdev.AI/tree/main#remove-imagedirectories) | removeimgdir | Removes directories from the configured image directories for GenXdev.AI operations. |
| [Remove-ImageMetaData](https://github.com/genXdev/GenXdev.AI/tree/main#remove-imagemetadata) | removeimagedata | Removes image metadata files from image directories. |
| [ResizeComfyInputImage](https://github.com/genXdev/GenXdev.AI/tree/main#resizecomfyinputimage) | &nbsp; | Resizes input image while preserving aspect ratio for optimal processing. |
| [Save-FoundImageFaces](https://github.com/genXdev/GenXdev.AI/tree/main#save-foundimagefaces) | saveimagefaces | Saves cropped face images from indexed image search results. |
| [Save-FoundImageObjects](https://github.com/genXdev/GenXdev.AI/tree/main#save-foundimageobjects) | saveimageObjects | Saves cropped object images from indexed image search results to files. |
| [Save-Transcriptions](https://github.com/genXdev/GenXdev.AI/tree/main#save-transcriptions) | &nbsp; | Generates subtitle files for audio and video files using OpenAI Whisper. |
| [Set-AIImageCollection](https://github.com/genXdev/GenXdev.AI/tree/main#set-aiimagecollection) | &nbsp; | &nbsp; |
| [Set-AIKnownFacesRootpath](https://github.com/genXdev/GenXdev.AI/tree/main#set-aiknownfacesrootpath) | &nbsp; | Sets the directory for face image files used in GenXdev.AI operations. |
| [Set-AILLMSettings](https://github.com/genXdev/GenXdev.AI/tree/main#set-aillmsettings) | &nbsp; | Sets the LLM settings for AI operations in GenXdev.AI. |
| [Set-AIMetaLanguage](https://github.com/genXdev/GenXdev.AI/tree/main#set-aimetalanguage) | &nbsp; | &nbsp; |
| [Set-ComfyUIBackgroundImage](https://github.com/genXdev/GenXdev.AI/tree/main#set-comfyuibackgroundimage) | &nbsp; | Sets or clears the background image for ComfyUI's canvas interface |
| [Set-ComfyUIModelPath](https://github.com/genXdev/GenXdev.AI/tree/main#set-comfyuimodelpath) | &nbsp; | Adds a custom model path to ComfyUI's extra_model_paths.yaml configuration |
| [Set-GenXdevAICommandNotFoundAction](https://github.com/genXdev/GenXdev.AI/tree/main#set-genxdevaicommandnotfoundaction) | &nbsp; | Sets up custom command not found handling with AI assistance. |
| [Set-ImageIndexPath](https://github.com/genXdev/GenXdev.AI/tree/main#set-imageindexpath) | &nbsp; | Sets the default database file path for image operations in GenXdev.AI. |
| [Set-WindowsWallpaperEx](https://github.com/genXdev/GenXdev.AI/tree/main#set-windowswallpaperex) | nextwallpaper | Sets a random wallpaper from a specified directory or search criteria. |
| [SetComfyUIProcessPriority](https://github.com/genXdev/GenXdev.AI/tree/main#setcomfyuiprocesspriority) | &nbsp; | Sets ComfyUI processes to IDLE priority for CPU mode processing optimization. |
| [Show-FoundImagesInBrowser](https://github.com/genXdev/GenXdev.AI/tree/main#show-foundimagesinbrowser) | showfoundimages | Displays image search results in a masonry layout web gallery. |
| [Show-GenXdevScriptErrorFixInIde](https://github.com/genXdev/GenXdev.AI/tree/main#show-genxdevscripterrorfixinide) | letsfixthis | Executes a script block and analyzes errors using AI to generate fixes in IDE. |
| [Start-AudioTranscription](https://github.com/genXdev/GenXdev.AI/tree/main#start-audiotranscription) | transcribe, transcribefile | Transcribes an audio file, video file, or a recording device to text |
| [Start-GenXdevMCPServer](https://github.com/genXdev/GenXdev.AI/tree/main#start-genxdevmcpserver) | &nbsp; | Starts the GenXdev MCP server that exposes PowerShell cmdlets as tools. |
| [Start-LMStudioApplication](https://github.com/genXdev/GenXdev.AI/tree/main#start-lmstudioapplication) | &nbsp; | Starts the LM Studio application if it's not already running. |
| [Stop-ComfyUI](https://github.com/genXdev/GenXdev.AI/tree/main#stop-comfyui) | &nbsp; | Terminates all running ComfyUI processes and releases associated resources. |
| [Test-ComfyUIQueueEmpty](https://github.com/genXdev/GenXdev.AI/tree/main#test-comfyuiqueueempty) | &nbsp; | Checks if the ComfyUI processing queue is empty |
| [Test-DeepLinkImageFile](https://github.com/genXdev/GenXdev.AI/tree/main#test-deeplinkimagefile) | &nbsp; | Tests if the specified file path is a valid image file with a supported format. |
| [Test-LMStudioInstallation](https://github.com/genXdev/GenXdev.AI/tree/main#test-lmstudioinstallation) | &nbsp; | Tests if LMStudio is installed and accessible on the system. |
| [Test-LMStudioProcess](https://github.com/genXdev/GenXdev.AI/tree/main#test-lmstudioprocess) | &nbsp; | Tests if LM Studio process is running and configures its window state. |
| [Unregister-AllFaces](https://github.com/genXdev/GenXdev.AI/tree/main#unregister-allfaces) | &nbsp; | Removes all registered faces from the DeepStack face recognition system. |
| [Unregister-Face](https://github.com/genXdev/GenXdev.AI/tree/main#unregister-face) | &nbsp; | Deletes a registered face by its identifier from DeepStack. |
| [Update-AllImageMetaData](https://github.com/genXdev/GenXdev.AI/tree/main#update-allimagemetadata) | updateallimages | &nbsp; |
| [UploadComfyImage](https://github.com/genXdev/GenXdev.AI/tree/main#uploadcomfyimage) | &nbsp; | Uploads image file to ComfyUI server for processing workflow integration. |
| [WaitForComfyCompletion](https://github.com/genXdev/GenXdev.AI/tree/main#waitforcomfycompletion) | &nbsp; | Waits for ComfyUI workflow completion with progress monitoring |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.AI/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.AI.ComfyUI

**A Windows PowerShell module for local AI related operations**

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [Add-EmoticonsToText](https://github.com/genXdev/GenXdev.AI/tree/main#add-emoticonstotext) | emojify | Enhances text by adding contextually appropriate emoticons using AI. |
| [Add-GenXdevMCPServerToLMStudio](https://github.com/genXdev/GenXdev.AI/tree/main#add-genxdevmcpservertolmstudio) | &nbsp; | Adds the GenXdev MCP server to LM Studio using a deeplink configuration. |
| [Add-ImageDirectories](https://github.com/genXdev/GenXdev.AI/tree/main#add-imagedirectories) | addimgdir | Adds directories to the configured image directories for GenXdev.AI operations. |
| [Approve-NewTextFileContent](https://github.com/genXdev/GenXdev.AI/tree/main#approve-newtextfilecontent) | &nbsp; | Interactive file content comparison and approval using WinMerge. |
| [Compare-ImageFaces](https://github.com/genXdev/GenXdev.AI/tree/main#compare-imagefaces) | comparefaces | Processes the face match result from DeepStack API. |
| [Convert-DotNetTypeToLLMType](https://github.com/genXdev/GenXdev.AI/tree/main#convert-dotnettypetollmtype) | &nbsp; | Converts .NET type names to LLM (Language Model) type names. |
| [ConvertComfyImageFormat](https://github.com/genXdev/GenXdev.AI/tree/main#convertcomfyimageformat) | &nbsp; | Converts image file format while preserving maximum quality. |
| [ConvertFrom-CorporateSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertfrom-corporatespeak) | uncorporatize | Converts polite, professional corporate speak into direct, clear language using AI. |
| [ConvertFrom-DiplomaticSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertfrom-diplomaticspeak) | undiplomatize | &nbsp; |
| [ConvertTo-CorporateSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertto-corporatespeak) | corporatize | Converts direct or blunt text into polite, professional corporate speak using AI. |
| [ConvertTo-DiplomaticSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertto-diplomaticspeak) | diplomatize | Converts direct or blunt text into polite, tactful diplomatic language. |
| [ConvertTo-LMStudioFunctionDefinition](https://github.com/genXdev/GenXdev.AI/tree/main#convertto-lmstudiofunctiondefinition) | &nbsp; | Converts PowerShell functions to LMStudio function definitions. |
| [CreateComfySDXLWorkflow](https://github.com/genXdev/GenXdev.AI/tree/main#createcomfysdxlworkflow) | &nbsp; | Creates comprehensive ComfyUI SDXL workflow configuration supporting all parameters |
| [CreateComfyUniversalWorkflow](https://github.com/genXdev/GenXdev.AI/tree/main#createcomfyuniversalworkflow) | &nbsp; | Creates comprehensive ComfyUI workflow configuration supporting all parameters |
| [DownloadComfyResults](https://github.com/genXdev/GenXdev.AI/tree/main#downloadcomfyresults) | &nbsp; | Downloads generated results from ComfyUI server with file information |
| [EnsureComfyUI](https://github.com/genXdev/GenXdev.AI/tree/main#ensurecomfyui) | &nbsp; | Ensures ComfyUI is installed and running with optional window positioning. |
| [EnsureComfyUIModel](https://github.com/genXdev/GenXdev.AI/tree/main#ensurecomfyuimodel) | &nbsp; | Ensures specified ComfyUI models are available locally with automatic download |
| [EnsureDeepStack](https://github.com/genXdev/GenXdev.AI/tree/main#ensuredeepstack) | &nbsp; | Ensures DeepStack face recognition service is installed and running. |
| [EnsureGithubCLIInstalled](https://github.com/genXdev/GenXdev.AI/tree/main#ensuregithubcliinstalled) | &nbsp; | Ensures GitHub CLI is properly installed and configured on the system. |
| [EnsureHuggingFace](https://github.com/genXdev/GenXdev.AI/tree/main#ensurehuggingface) | &nbsp; | Ensures the Hugging Face CLI is installed and functional. |
| [EnsureLMStudio](https://github.com/genXdev/GenXdev.AI/tree/main#ensurelmstudio) | &nbsp; | Ensures LM Studio is properly initialized with the specified model. |
| [EnsurePaintNet](https://github.com/genXdev/GenXdev.AI/tree/main#ensurepaintnet) | &nbsp; | Ensures Paint.NET is properly installed and accessible on the system. |
| [EnsurePip](https://github.com/genXdev/GenXdev.AI/tree/main#ensurepip) | &nbsp; | Ensures pip is installed and functional for the specified Python installation. |
| [EnsurePython](https://github.com/genXdev/GenXdev.AI/tree/main#ensurepython) | &nbsp; | Ensures Python is installed and available in the system PATH. |
| [EnsureWinMergeInstalled](https://github.com/genXdev/GenXdev.AI/tree/main#ensurewinmergeinstalled) | &nbsp; | Ensures WinMerge is installed and available for file comparison operations. |
| [Export-ImageIndex](https://github.com/genXdev/GenXdev.AI/tree/main#export-imageindex) | indeximages | Initializes and populates the SQLite database by discovering images directly. |
| [Find-Image](https://github.com/genXdev/GenXdev.AI/tree/main#find-image) | findimages, li | &nbsp; |
| [Find-IndexedImage](https://github.com/genXdev/GenXdev.AI/tree/main#find-indexedimage) | findindexedimages, lii | Searches for images using an optimized SQLite database with fast indexed lookups. |
| [GenerateMasonryLayoutHtml](https://github.com/genXdev/GenXdev.AI/tree/main#generatemasonrylayouthtml) | &nbsp; | Generates a responsive masonry layout HTML gallery from image data. |
| [Get-AIDefaultLLMSettings](https://github.com/genXdev/GenXdev.AI/tree/main#get-aidefaultllmsettings) | &nbsp; | Gets all available default LLM settings configurations for AI operations in GenXdev.AI. |
| [Get-AIImageCollection](https://github.com/genXdev/GenXdev.AI/tree/main#get-aiimagecollection) | getimgdirs | Gets the configured directories for image files used in GenXdev.AI operations. |
| [Get-AIKnownFacesRootpath](https://github.com/genXdev/GenXdev.AI/tree/main#get-aiknownfacesrootpath) | &nbsp; | &nbsp; |
| [Get-AILLMSettings](https://github.com/genXdev/GenXdev.AI/tree/main#get-aillmsettings) | &nbsp; | Gets the LLM settings for AI operations in GenXdev.AI. |
| [Get-AIMetaLanguage](https://github.com/genXdev/GenXdev.AI/tree/main#get-aimetalanguage) | getimgmetalang | Gets the configured default language for image metadata operations. |
| [Get-ComfyUIModelPath](https://github.com/genXdev/GenXdev.AI/tree/main#get-comfyuimodelpath) | &nbsp; | Gets the correct ComfyUI models directory path for the current installation |
| [Get-CpuCore](https://github.com/genXdev/GenXdev.AI/tree/main#get-cpucore) | &nbsp; | Calculates and returns the total number of logical CPU cores in the system. |
| [Get-Fallacy](https://github.com/genXdev/GenXdev.AI/tree/main#get-fallacy) | dispicetext | Analyzes text to identify logical fallacies using AI-powered detection. |
| [Get-HasCapableGpu](https://github.com/genXdev/GenXdev.AI/tree/main#get-hascapablegpu) | &nbsp; | Determines if a CUDA-capable GPU with sufficient memory is present. |
| [Get-ImageDetectedFaces](https://github.com/genXdev/GenXdev.AI/tree/main#get-imagedetectedfaces) | &nbsp; | &nbsp; |
| [Get-ImageDetectedObjects](https://github.com/genXdev/GenXdev.AI/tree/main#get-imagedetectedobjects) | &nbsp; | Detects and classifies objects in an uploaded image using DeepStack. |
| [Get-ImageDetectedScenes](https://github.com/genXdev/GenXdev.AI/tree/main#get-imagedetectedscenes) | &nbsp; | Classifies an image into one of 365 scene categories using DeepStack. |
| [Get-ImageIndexPath](https://github.com/genXdev/GenXdev.AI/tree/main#get-imageindexpath) | &nbsp; | Returns the path to the image database, initializing or rebuilding it if needed. |
| [Get-ImageIndexStats](https://github.com/genXdev/GenXdev.AI/tree/main#get-imageindexstats) | getimagedbstats, gids | Retrieves comprehensive statistics and information about the image database. |
| [Get-LMStudioLoadedModelList](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudioloadedmodellist) | &nbsp; | Retrieves the list of currently loaded models from LM Studio. |
| [Get-LMStudioModelList](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiomodellist) | &nbsp; | Retrieves a list of installed LM Studio models. |
| [Get-LMStudioPaths](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiopaths) | &nbsp; | Retrieves file paths for LM Studio executables. |
| [Get-LMStudioTextEmbedding](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiotextembedding) | &nbsp; | Gets text embeddings from LM Studio model. |
| [Get-LMStudioWindow](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiowindow) | lmstudiowindow, setlmstudiowindow | Gets a window helper for the LM Studio application. |
| [Get-NumberOfCpuCores](https://github.com/genXdev/GenXdev.AI/tree/main#get-numberofcpucores) | &nbsp; | Calculates and returns the total number of logical CPU cores in the system. |
| [Get-RegisteredFaces](https://github.com/genXdev/GenXdev.AI/tree/main#get-registeredfaces) | &nbsp; | Retrieves a list of all registered face identifiers from DeepStack. |
| [Get-ScriptExecutionErrorFixPrompt](https://github.com/genXdev/GenXdev.AI/tree/main#get-scriptexecutionerrorfixprompt) | getfixprompt | Captures error messages from various streams and uses LLM to suggest fixes. |
| [Get-SimularMovieTitles](https://github.com/genXdev/GenXdev.AI/tree/main#get-simularmovietitles) | &nbsp; | Finds similar movie titles based on common properties. |
| [Get-TextTranslation](https://github.com/genXdev/GenXdev.AI/tree/main#get-texttranslation) | translate | Translates text to another language using AI. |
| [Get-VectorSimilarity](https://github.com/genXdev/GenXdev.AI/tree/main#get-vectorsimilarity) | &nbsp; | &nbsp; |
| [Initialize-LMStudioModel](https://github.com/genXdev/GenXdev.AI/tree/main#initialize-lmstudiomodel) | initlmstudio | Initializes and loads an AI model in LM Studio. |
| [Install-LMStudioApplication](https://github.com/genXdev/GenXdev.AI/tree/main#install-lmstudioapplication) | &nbsp; | Installs LM Studio application using WinGet package manager. |
| [Invoke-AIPowershellCommand](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-aipowershellcommand) | hint | Converts AI command suggestions to JSON format for processing. |
| [Invoke-ComfyUIImageGeneration](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-comfyuiimagegeneration) | generateimage | &nbsp; |
| [Invoke-CommandFromToolCall](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-commandfromtoolcall) | &nbsp; | Executes a tool call function with validation and parameter filtering. |
| [Invoke-HuggingFaceCli](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-huggingfacecli) | &nbsp; | Invokes the Hugging Face CLI with the specified arguments. |
| [Invoke-ImageEnhancement](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imageenhancement) | enhanceimage | Enhances an image by enlarging it 4X while improving quality using DeepStack. |
| [Invoke-ImageFacesUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagefacesupdate) | imagepeopledetection | Updates face recognition metadata for image files in a specified directory. |
| [Invoke-ImageKeywordUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagekeywordupdate) | imagekeywordgeneration | Updates image metadata with AI-generated descriptions and keywords. |
| [Invoke-ImageMetadataUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagemetadataupdate) | imagepropdetection | Updates EXIF metadata for images in a directory. |
| [Invoke-ImageObjectsUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imageobjectsupdate) | imageobjectdetection | Updates object detection metadata for image files in a specified directory. |
| [Invoke-ImageScenesUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagescenesupdate) | imagescenedetection | Updates scene classification metadata for image files in a specified directory. |
| [Invoke-LLMBooleanEvaluation](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmbooleanevaluation) | equalstrue | Evaluates a statement using AI to determine if it's true or false. |
| [Invoke-LLMQuery](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmquery) | llm, qllm | &nbsp; |
| [Invoke-LLMStringListEvaluation](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmstringlistevaluation) | getlist, getstring | &nbsp; |
| [Invoke-LLMTextTransformation](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmtexttransformation) | spellcheck | Transforms text using AI-powered processing. |
| [Invoke-QueryImageContent](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-queryimagecontent) | &nbsp; | Analyzes image content using AI vision capabilities through the LM-Studio API. |
| [Invoke-WinMerge](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-winmerge) | &nbsp; | Launches WinMerge to compare two files side by side. |
| [New-LLMAudioChat](https://github.com/genXdev/GenXdev.AI/tree/main#new-llmaudiochat) | llmaudiochat | Creates an interactive audio chat session with an LLM model. |
| [New-LLMTextChat](https://github.com/genXdev/GenXdev.AI/tree/main#new-llmtextchat) | llmchat | Starts an interactive text chat session with AI capabilities. |
| [QueueComfyWorkflow](https://github.com/genXdev/GenXdev.AI/tree/main#queuecomfyworkflow) | &nbsp; | Submits workflow to ComfyUI processing queue for execution. |
| [Register-AllFaces](https://github.com/genXdev/GenXdev.AI/tree/main#register-allfaces) | UpdateFaces | Updates all face recognition profiles from image files in the faces directory. |
| [Register-Face](https://github.com/genXdev/GenXdev.AI/tree/main#register-face) | &nbsp; | Registers a new face with the DeepStack face recognition API. |
| [Remove-ImageDirectories](https://github.com/genXdev/GenXdev.AI/tree/main#remove-imagedirectories) | removeimgdir | Removes directories from the configured image directories for GenXdev.AI operations. |
| [Remove-ImageMetaData](https://github.com/genXdev/GenXdev.AI/tree/main#remove-imagemetadata) | removeimagedata | Removes image metadata files from image directories. |
| [ResizeComfyInputImage](https://github.com/genXdev/GenXdev.AI/tree/main#resizecomfyinputimage) | &nbsp; | Resizes input image while preserving aspect ratio for optimal processing. |
| [Save-FoundImageFaces](https://github.com/genXdev/GenXdev.AI/tree/main#save-foundimagefaces) | saveimagefaces | Saves cropped face images from indexed image search results. |
| [Save-FoundImageObjects](https://github.com/genXdev/GenXdev.AI/tree/main#save-foundimageobjects) | saveimageObjects | Saves cropped object images from indexed image search results to files. |
| [Save-Transcriptions](https://github.com/genXdev/GenXdev.AI/tree/main#save-transcriptions) | &nbsp; | Generates subtitle files for audio and video files using OpenAI Whisper. |
| [Set-AIImageCollection](https://github.com/genXdev/GenXdev.AI/tree/main#set-aiimagecollection) | &nbsp; | &nbsp; |
| [Set-AIKnownFacesRootpath](https://github.com/genXdev/GenXdev.AI/tree/main#set-aiknownfacesrootpath) | &nbsp; | Sets the directory for face image files used in GenXdev.AI operations. |
| [Set-AILLMSettings](https://github.com/genXdev/GenXdev.AI/tree/main#set-aillmsettings) | &nbsp; | Sets the LLM settings for AI operations in GenXdev.AI. |
| [Set-AIMetaLanguage](https://github.com/genXdev/GenXdev.AI/tree/main#set-aimetalanguage) | &nbsp; | &nbsp; |
| [Set-ComfyUIBackgroundImage](https://github.com/genXdev/GenXdev.AI/tree/main#set-comfyuibackgroundimage) | &nbsp; | Sets or clears the background image for ComfyUI's canvas interface |
| [Set-ComfyUIModelPath](https://github.com/genXdev/GenXdev.AI/tree/main#set-comfyuimodelpath) | &nbsp; | Adds a custom model path to ComfyUI's extra_model_paths.yaml configuration |
| [Set-GenXdevAICommandNotFoundAction](https://github.com/genXdev/GenXdev.AI/tree/main#set-genxdevaicommandnotfoundaction) | &nbsp; | Sets up custom command not found handling with AI assistance. |
| [Set-ImageIndexPath](https://github.com/genXdev/GenXdev.AI/tree/main#set-imageindexpath) | &nbsp; | Sets the default database file path for image operations in GenXdev.AI. |
| [Set-WindowsWallpaperEx](https://github.com/genXdev/GenXdev.AI/tree/main#set-windowswallpaperex) | nextwallpaper | Sets a random wallpaper from a specified directory or search criteria. |
| [SetComfyUIProcessPriority](https://github.com/genXdev/GenXdev.AI/tree/main#setcomfyuiprocesspriority) | &nbsp; | Sets ComfyUI processes to IDLE priority for CPU mode processing optimization. |
| [Show-FoundImagesInBrowser](https://github.com/genXdev/GenXdev.AI/tree/main#show-foundimagesinbrowser) | showfoundimages | Displays image search results in a masonry layout web gallery. |
| [Show-GenXdevScriptErrorFixInIde](https://github.com/genXdev/GenXdev.AI/tree/main#show-genxdevscripterrorfixinide) | letsfixthis | Executes a script block and analyzes errors using AI to generate fixes in IDE. |
| [Start-AudioTranscription](https://github.com/genXdev/GenXdev.AI/tree/main#start-audiotranscription) | transcribe, transcribefile | Transcribes an audio file, video file, or a recording device to text |
| [Start-GenXdevMCPServer](https://github.com/genXdev/GenXdev.AI/tree/main#start-genxdevmcpserver) | &nbsp; | Starts the GenXdev MCP server that exposes PowerShell cmdlets as tools. |
| [Start-LMStudioApplication](https://github.com/genXdev/GenXdev.AI/tree/main#start-lmstudioapplication) | &nbsp; | Starts the LM Studio application if it's not already running. |
| [Stop-ComfyUI](https://github.com/genXdev/GenXdev.AI/tree/main#stop-comfyui) | &nbsp; | Terminates all running ComfyUI processes and releases associated resources. |
| [Test-ComfyUIQueueEmpty](https://github.com/genXdev/GenXdev.AI/tree/main#test-comfyuiqueueempty) | &nbsp; | Checks if the ComfyUI processing queue is empty |
| [Test-DeepLinkImageFile](https://github.com/genXdev/GenXdev.AI/tree/main#test-deeplinkimagefile) | &nbsp; | Tests if the specified file path is a valid image file with a supported format. |
| [Test-LMStudioInstallation](https://github.com/genXdev/GenXdev.AI/tree/main#test-lmstudioinstallation) | &nbsp; | Tests if LMStudio is installed and accessible on the system. |
| [Test-LMStudioProcess](https://github.com/genXdev/GenXdev.AI/tree/main#test-lmstudioprocess) | &nbsp; | Tests if LM Studio process is running and configures its window state. |
| [Unregister-AllFaces](https://github.com/genXdev/GenXdev.AI/tree/main#unregister-allfaces) | &nbsp; | Removes all registered faces from the DeepStack face recognition system. |
| [Unregister-Face](https://github.com/genXdev/GenXdev.AI/tree/main#unregister-face) | &nbsp; | Deletes a registered face by its identifier from DeepStack. |
| [Update-AllImageMetaData](https://github.com/genXdev/GenXdev.AI/tree/main#update-allimagemetadata) | updateallimages | &nbsp; |
| [UploadComfyImage](https://github.com/genXdev/GenXdev.AI/tree/main#uploadcomfyimage) | &nbsp; | Uploads image file to ComfyUI server for processing workflow integration. |
| [WaitForComfyCompletion](https://github.com/genXdev/GenXdev.AI/tree/main#waitforcomfycompletion) | &nbsp; | Waits for ComfyUI workflow completion with progress monitoring |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.AI/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.AI.Data

**A Windows PowerShell module for local AI related operations**

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [Add-EmoticonsToText](https://github.com/genXdev/GenXdev.AI/tree/main#add-emoticonstotext) | emojify | Enhances text by adding contextually appropriate emoticons using AI. |
| [Add-GenXdevMCPServerToLMStudio](https://github.com/genXdev/GenXdev.AI/tree/main#add-genxdevmcpservertolmstudio) | &nbsp; | Adds the GenXdev MCP server to LM Studio using a deeplink configuration. |
| [Add-ImageDirectories](https://github.com/genXdev/GenXdev.AI/tree/main#add-imagedirectories) | addimgdir | Adds directories to the configured image directories for GenXdev.AI operations. |
| [Approve-NewTextFileContent](https://github.com/genXdev/GenXdev.AI/tree/main#approve-newtextfilecontent) | &nbsp; | Interactive file content comparison and approval using WinMerge. |
| [Compare-ImageFaces](https://github.com/genXdev/GenXdev.AI/tree/main#compare-imagefaces) | comparefaces | Processes the face match result from DeepStack API. |
| [Convert-DotNetTypeToLLMType](https://github.com/genXdev/GenXdev.AI/tree/main#convert-dotnettypetollmtype) | &nbsp; | Converts .NET type names to LLM (Language Model) type names. |
| [ConvertComfyImageFormat](https://github.com/genXdev/GenXdev.AI/tree/main#convertcomfyimageformat) | &nbsp; | Converts image file format while preserving maximum quality. |
| [ConvertFrom-CorporateSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertfrom-corporatespeak) | uncorporatize | Converts polite, professional corporate speak into direct, clear language using AI. |
| [ConvertFrom-DiplomaticSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertfrom-diplomaticspeak) | undiplomatize | &nbsp; |
| [ConvertTo-CorporateSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertto-corporatespeak) | corporatize | Converts direct or blunt text into polite, professional corporate speak using AI. |
| [ConvertTo-DiplomaticSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertto-diplomaticspeak) | diplomatize | Converts direct or blunt text into polite, tactful diplomatic language. |
| [ConvertTo-LMStudioFunctionDefinition](https://github.com/genXdev/GenXdev.AI/tree/main#convertto-lmstudiofunctiondefinition) | &nbsp; | Converts PowerShell functions to LMStudio function definitions. |
| [CreateComfySDXLWorkflow](https://github.com/genXdev/GenXdev.AI/tree/main#createcomfysdxlworkflow) | &nbsp; | Creates comprehensive ComfyUI SDXL workflow configuration supporting all parameters |
| [CreateComfyUniversalWorkflow](https://github.com/genXdev/GenXdev.AI/tree/main#createcomfyuniversalworkflow) | &nbsp; | Creates comprehensive ComfyUI workflow configuration supporting all parameters |
| [DownloadComfyResults](https://github.com/genXdev/GenXdev.AI/tree/main#downloadcomfyresults) | &nbsp; | Downloads generated results from ComfyUI server with file information |
| [EnsureComfyUI](https://github.com/genXdev/GenXdev.AI/tree/main#ensurecomfyui) | &nbsp; | Ensures ComfyUI is installed and running with optional window positioning. |
| [EnsureComfyUIModel](https://github.com/genXdev/GenXdev.AI/tree/main#ensurecomfyuimodel) | &nbsp; | Ensures specified ComfyUI models are available locally with automatic download |
| [EnsureDeepStack](https://github.com/genXdev/GenXdev.AI/tree/main#ensuredeepstack) | &nbsp; | Ensures DeepStack face recognition service is installed and running. |
| [EnsureGithubCLIInstalled](https://github.com/genXdev/GenXdev.AI/tree/main#ensuregithubcliinstalled) | &nbsp; | Ensures GitHub CLI is properly installed and configured on the system. |
| [EnsureHuggingFace](https://github.com/genXdev/GenXdev.AI/tree/main#ensurehuggingface) | &nbsp; | Ensures the Hugging Face CLI is installed and functional. |
| [EnsureLMStudio](https://github.com/genXdev/GenXdev.AI/tree/main#ensurelmstudio) | &nbsp; | Ensures LM Studio is properly initialized with the specified model. |
| [EnsurePaintNet](https://github.com/genXdev/GenXdev.AI/tree/main#ensurepaintnet) | &nbsp; | Ensures Paint.NET is properly installed and accessible on the system. |
| [EnsurePip](https://github.com/genXdev/GenXdev.AI/tree/main#ensurepip) | &nbsp; | Ensures pip is installed and functional for the specified Python installation. |
| [EnsurePython](https://github.com/genXdev/GenXdev.AI/tree/main#ensurepython) | &nbsp; | Ensures Python is installed and available in the system PATH. |
| [EnsureWinMergeInstalled](https://github.com/genXdev/GenXdev.AI/tree/main#ensurewinmergeinstalled) | &nbsp; | Ensures WinMerge is installed and available for file comparison operations. |
| [Export-ImageIndex](https://github.com/genXdev/GenXdev.AI/tree/main#export-imageindex) | indeximages | Initializes and populates the SQLite database by discovering images directly. |
| [Find-Image](https://github.com/genXdev/GenXdev.AI/tree/main#find-image) | findimages, li | &nbsp; |
| [Find-IndexedImage](https://github.com/genXdev/GenXdev.AI/tree/main#find-indexedimage) | findindexedimages, lii | Searches for images using an optimized SQLite database with fast indexed lookups. |
| [GenerateMasonryLayoutHtml](https://github.com/genXdev/GenXdev.AI/tree/main#generatemasonrylayouthtml) | &nbsp; | Generates a responsive masonry layout HTML gallery from image data. |
| [Get-AIDefaultLLMSettings](https://github.com/genXdev/GenXdev.AI/tree/main#get-aidefaultllmsettings) | &nbsp; | Gets all available default LLM settings configurations for AI operations in GenXdev.AI. |
| [Get-AIImageCollection](https://github.com/genXdev/GenXdev.AI/tree/main#get-aiimagecollection) | getimgdirs | Gets the configured directories for image files used in GenXdev.AI operations. |
| [Get-AIKnownFacesRootpath](https://github.com/genXdev/GenXdev.AI/tree/main#get-aiknownfacesrootpath) | &nbsp; | &nbsp; |
| [Get-AILLMSettings](https://github.com/genXdev/GenXdev.AI/tree/main#get-aillmsettings) | &nbsp; | Gets the LLM settings for AI operations in GenXdev.AI. |
| [Get-AIMetaLanguage](https://github.com/genXdev/GenXdev.AI/tree/main#get-aimetalanguage) | getimgmetalang | Gets the configured default language for image metadata operations. |
| [Get-ComfyUIModelPath](https://github.com/genXdev/GenXdev.AI/tree/main#get-comfyuimodelpath) | &nbsp; | Gets the correct ComfyUI models directory path for the current installation |
| [Get-CpuCore](https://github.com/genXdev/GenXdev.AI/tree/main#get-cpucore) | &nbsp; | Calculates and returns the total number of logical CPU cores in the system. |
| [Get-Fallacy](https://github.com/genXdev/GenXdev.AI/tree/main#get-fallacy) | dispicetext | Analyzes text to identify logical fallacies using AI-powered detection. |
| [Get-HasCapableGpu](https://github.com/genXdev/GenXdev.AI/tree/main#get-hascapablegpu) | &nbsp; | Determines if a CUDA-capable GPU with sufficient memory is present. |
| [Get-ImageDetectedFaces](https://github.com/genXdev/GenXdev.AI/tree/main#get-imagedetectedfaces) | &nbsp; | &nbsp; |
| [Get-ImageDetectedObjects](https://github.com/genXdev/GenXdev.AI/tree/main#get-imagedetectedobjects) | &nbsp; | Detects and classifies objects in an uploaded image using DeepStack. |
| [Get-ImageDetectedScenes](https://github.com/genXdev/GenXdev.AI/tree/main#get-imagedetectedscenes) | &nbsp; | Classifies an image into one of 365 scene categories using DeepStack. |
| [Get-ImageIndexPath](https://github.com/genXdev/GenXdev.AI/tree/main#get-imageindexpath) | &nbsp; | Returns the path to the image database, initializing or rebuilding it if needed. |
| [Get-ImageIndexStats](https://github.com/genXdev/GenXdev.AI/tree/main#get-imageindexstats) | getimagedbstats, gids | Retrieves comprehensive statistics and information about the image database. |
| [Get-LMStudioLoadedModelList](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudioloadedmodellist) | &nbsp; | Retrieves the list of currently loaded models from LM Studio. |
| [Get-LMStudioModelList](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiomodellist) | &nbsp; | Retrieves a list of installed LM Studio models. |
| [Get-LMStudioPaths](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiopaths) | &nbsp; | Retrieves file paths for LM Studio executables. |
| [Get-LMStudioTextEmbedding](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiotextembedding) | &nbsp; | Gets text embeddings from LM Studio model. |
| [Get-LMStudioWindow](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiowindow) | lmstudiowindow, setlmstudiowindow | Gets a window helper for the LM Studio application. |
| [Get-NumberOfCpuCores](https://github.com/genXdev/GenXdev.AI/tree/main#get-numberofcpucores) | &nbsp; | Calculates and returns the total number of logical CPU cores in the system. |
| [Get-RegisteredFaces](https://github.com/genXdev/GenXdev.AI/tree/main#get-registeredfaces) | &nbsp; | Retrieves a list of all registered face identifiers from DeepStack. |
| [Get-ScriptExecutionErrorFixPrompt](https://github.com/genXdev/GenXdev.AI/tree/main#get-scriptexecutionerrorfixprompt) | getfixprompt | Captures error messages from various streams and uses LLM to suggest fixes. |
| [Get-SimularMovieTitles](https://github.com/genXdev/GenXdev.AI/tree/main#get-simularmovietitles) | &nbsp; | Finds similar movie titles based on common properties. |
| [Get-TextTranslation](https://github.com/genXdev/GenXdev.AI/tree/main#get-texttranslation) | translate | Translates text to another language using AI. |
| [Get-VectorSimilarity](https://github.com/genXdev/GenXdev.AI/tree/main#get-vectorsimilarity) | &nbsp; | &nbsp; |
| [Initialize-LMStudioModel](https://github.com/genXdev/GenXdev.AI/tree/main#initialize-lmstudiomodel) | initlmstudio | Initializes and loads an AI model in LM Studio. |
| [Install-LMStudioApplication](https://github.com/genXdev/GenXdev.AI/tree/main#install-lmstudioapplication) | &nbsp; | Installs LM Studio application using WinGet package manager. |
| [Invoke-AIPowershellCommand](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-aipowershellcommand) | hint | Converts AI command suggestions to JSON format for processing. |
| [Invoke-ComfyUIImageGeneration](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-comfyuiimagegeneration) | generateimage | &nbsp; |
| [Invoke-CommandFromToolCall](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-commandfromtoolcall) | &nbsp; | Executes a tool call function with validation and parameter filtering. |
| [Invoke-HuggingFaceCli](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-huggingfacecli) | &nbsp; | Invokes the Hugging Face CLI with the specified arguments. |
| [Invoke-ImageEnhancement](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imageenhancement) | enhanceimage | Enhances an image by enlarging it 4X while improving quality using DeepStack. |
| [Invoke-ImageFacesUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagefacesupdate) | imagepeopledetection | Updates face recognition metadata for image files in a specified directory. |
| [Invoke-ImageKeywordUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagekeywordupdate) | imagekeywordgeneration | Updates image metadata with AI-generated descriptions and keywords. |
| [Invoke-ImageMetadataUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagemetadataupdate) | imagepropdetection | Updates EXIF metadata for images in a directory. |
| [Invoke-ImageObjectsUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imageobjectsupdate) | imageobjectdetection | Updates object detection metadata for image files in a specified directory. |
| [Invoke-ImageScenesUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagescenesupdate) | imagescenedetection | Updates scene classification metadata for image files in a specified directory. |
| [Invoke-LLMBooleanEvaluation](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmbooleanevaluation) | equalstrue | Evaluates a statement using AI to determine if it's true or false. |
| [Invoke-LLMQuery](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmquery) | llm, qllm | &nbsp; |
| [Invoke-LLMStringListEvaluation](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmstringlistevaluation) | getlist, getstring | &nbsp; |
| [Invoke-LLMTextTransformation](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmtexttransformation) | spellcheck | Transforms text using AI-powered processing. |
| [Invoke-QueryImageContent](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-queryimagecontent) | &nbsp; | Analyzes image content using AI vision capabilities through the LM-Studio API. |
| [Invoke-WinMerge](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-winmerge) | &nbsp; | Launches WinMerge to compare two files side by side. |
| [New-LLMAudioChat](https://github.com/genXdev/GenXdev.AI/tree/main#new-llmaudiochat) | llmaudiochat | Creates an interactive audio chat session with an LLM model. |
| [New-LLMTextChat](https://github.com/genXdev/GenXdev.AI/tree/main#new-llmtextchat) | llmchat | Starts an interactive text chat session with AI capabilities. |
| [QueueComfyWorkflow](https://github.com/genXdev/GenXdev.AI/tree/main#queuecomfyworkflow) | &nbsp; | Submits workflow to ComfyUI processing queue for execution. |
| [Register-AllFaces](https://github.com/genXdev/GenXdev.AI/tree/main#register-allfaces) | UpdateFaces | Updates all face recognition profiles from image files in the faces directory. |
| [Register-Face](https://github.com/genXdev/GenXdev.AI/tree/main#register-face) | &nbsp; | Registers a new face with the DeepStack face recognition API. |
| [Remove-ImageDirectories](https://github.com/genXdev/GenXdev.AI/tree/main#remove-imagedirectories) | removeimgdir | Removes directories from the configured image directories for GenXdev.AI operations. |
| [Remove-ImageMetaData](https://github.com/genXdev/GenXdev.AI/tree/main#remove-imagemetadata) | removeimagedata | Removes image metadata files from image directories. |
| [ResizeComfyInputImage](https://github.com/genXdev/GenXdev.AI/tree/main#resizecomfyinputimage) | &nbsp; | Resizes input image while preserving aspect ratio for optimal processing. |
| [Save-FoundImageFaces](https://github.com/genXdev/GenXdev.AI/tree/main#save-foundimagefaces) | saveimagefaces | Saves cropped face images from indexed image search results. |
| [Save-FoundImageObjects](https://github.com/genXdev/GenXdev.AI/tree/main#save-foundimageobjects) | saveimageObjects | Saves cropped object images from indexed image search results to files. |
| [Save-Transcriptions](https://github.com/genXdev/GenXdev.AI/tree/main#save-transcriptions) | &nbsp; | Generates subtitle files for audio and video files using OpenAI Whisper. |
| [Set-AIImageCollection](https://github.com/genXdev/GenXdev.AI/tree/main#set-aiimagecollection) | &nbsp; | &nbsp; |
| [Set-AIKnownFacesRootpath](https://github.com/genXdev/GenXdev.AI/tree/main#set-aiknownfacesrootpath) | &nbsp; | Sets the directory for face image files used in GenXdev.AI operations. |
| [Set-AILLMSettings](https://github.com/genXdev/GenXdev.AI/tree/main#set-aillmsettings) | &nbsp; | Sets the LLM settings for AI operations in GenXdev.AI. |
| [Set-AIMetaLanguage](https://github.com/genXdev/GenXdev.AI/tree/main#set-aimetalanguage) | &nbsp; | &nbsp; |
| [Set-ComfyUIBackgroundImage](https://github.com/genXdev/GenXdev.AI/tree/main#set-comfyuibackgroundimage) | &nbsp; | Sets or clears the background image for ComfyUI's canvas interface |
| [Set-ComfyUIModelPath](https://github.com/genXdev/GenXdev.AI/tree/main#set-comfyuimodelpath) | &nbsp; | Adds a custom model path to ComfyUI's extra_model_paths.yaml configuration |
| [Set-GenXdevAICommandNotFoundAction](https://github.com/genXdev/GenXdev.AI/tree/main#set-genxdevaicommandnotfoundaction) | &nbsp; | Sets up custom command not found handling with AI assistance. |
| [Set-ImageIndexPath](https://github.com/genXdev/GenXdev.AI/tree/main#set-imageindexpath) | &nbsp; | Sets the default database file path for image operations in GenXdev.AI. |
| [Set-WindowsWallpaperEx](https://github.com/genXdev/GenXdev.AI/tree/main#set-windowswallpaperex) | nextwallpaper | Sets a random wallpaper from a specified directory or search criteria. |
| [SetComfyUIProcessPriority](https://github.com/genXdev/GenXdev.AI/tree/main#setcomfyuiprocesspriority) | &nbsp; | Sets ComfyUI processes to IDLE priority for CPU mode processing optimization. |
| [Show-FoundImagesInBrowser](https://github.com/genXdev/GenXdev.AI/tree/main#show-foundimagesinbrowser) | showfoundimages | Displays image search results in a masonry layout web gallery. |
| [Show-GenXdevScriptErrorFixInIde](https://github.com/genXdev/GenXdev.AI/tree/main#show-genxdevscripterrorfixinide) | letsfixthis | Executes a script block and analyzes errors using AI to generate fixes in IDE. |
| [Start-AudioTranscription](https://github.com/genXdev/GenXdev.AI/tree/main#start-audiotranscription) | transcribe, transcribefile | Transcribes an audio file, video file, or a recording device to text |
| [Start-GenXdevMCPServer](https://github.com/genXdev/GenXdev.AI/tree/main#start-genxdevmcpserver) | &nbsp; | Starts the GenXdev MCP server that exposes PowerShell cmdlets as tools. |
| [Start-LMStudioApplication](https://github.com/genXdev/GenXdev.AI/tree/main#start-lmstudioapplication) | &nbsp; | Starts the LM Studio application if it's not already running. |
| [Stop-ComfyUI](https://github.com/genXdev/GenXdev.AI/tree/main#stop-comfyui) | &nbsp; | Terminates all running ComfyUI processes and releases associated resources. |
| [Test-ComfyUIQueueEmpty](https://github.com/genXdev/GenXdev.AI/tree/main#test-comfyuiqueueempty) | &nbsp; | Checks if the ComfyUI processing queue is empty |
| [Test-DeepLinkImageFile](https://github.com/genXdev/GenXdev.AI/tree/main#test-deeplinkimagefile) | &nbsp; | Tests if the specified file path is a valid image file with a supported format. |
| [Test-LMStudioInstallation](https://github.com/genXdev/GenXdev.AI/tree/main#test-lmstudioinstallation) | &nbsp; | Tests if LMStudio is installed and accessible on the system. |
| [Test-LMStudioProcess](https://github.com/genXdev/GenXdev.AI/tree/main#test-lmstudioprocess) | &nbsp; | Tests if LM Studio process is running and configures its window state. |
| [Unregister-AllFaces](https://github.com/genXdev/GenXdev.AI/tree/main#unregister-allfaces) | &nbsp; | Removes all registered faces from the DeepStack face recognition system. |
| [Unregister-Face](https://github.com/genXdev/GenXdev.AI/tree/main#unregister-face) | &nbsp; | Deletes a registered face by its identifier from DeepStack. |
| [Update-AllImageMetaData](https://github.com/genXdev/GenXdev.AI/tree/main#update-allimagemetadata) | updateallimages | &nbsp; |
| [UploadComfyImage](https://github.com/genXdev/GenXdev.AI/tree/main#uploadcomfyimage) | &nbsp; | Uploads image file to ComfyUI server for processing workflow integration. |
| [WaitForComfyCompletion](https://github.com/genXdev/GenXdev.AI/tree/main#waitforcomfycompletion) | &nbsp; | Waits for ComfyUI workflow completion with progress monitoring |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.AI/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.AI.DeepStack

**A Windows PowerShell module for local AI related operations**

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [Add-EmoticonsToText](https://github.com/genXdev/GenXdev.AI/tree/main#add-emoticonstotext) | emojify | Enhances text by adding contextually appropriate emoticons using AI. |
| [Add-GenXdevMCPServerToLMStudio](https://github.com/genXdev/GenXdev.AI/tree/main#add-genxdevmcpservertolmstudio) | &nbsp; | Adds the GenXdev MCP server to LM Studio using a deeplink configuration. |
| [Add-ImageDirectories](https://github.com/genXdev/GenXdev.AI/tree/main#add-imagedirectories) | addimgdir | Adds directories to the configured image directories for GenXdev.AI operations. |
| [Approve-NewTextFileContent](https://github.com/genXdev/GenXdev.AI/tree/main#approve-newtextfilecontent) | &nbsp; | Interactive file content comparison and approval using WinMerge. |
| [Compare-ImageFaces](https://github.com/genXdev/GenXdev.AI/tree/main#compare-imagefaces) | comparefaces | Processes the face match result from DeepStack API. |
| [Convert-DotNetTypeToLLMType](https://github.com/genXdev/GenXdev.AI/tree/main#convert-dotnettypetollmtype) | &nbsp; | Converts .NET type names to LLM (Language Model) type names. |
| [ConvertComfyImageFormat](https://github.com/genXdev/GenXdev.AI/tree/main#convertcomfyimageformat) | &nbsp; | Converts image file format while preserving maximum quality. |
| [ConvertFrom-CorporateSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertfrom-corporatespeak) | uncorporatize | Converts polite, professional corporate speak into direct, clear language using AI. |
| [ConvertFrom-DiplomaticSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertfrom-diplomaticspeak) | undiplomatize | &nbsp; |
| [ConvertTo-CorporateSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertto-corporatespeak) | corporatize | Converts direct or blunt text into polite, professional corporate speak using AI. |
| [ConvertTo-DiplomaticSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertto-diplomaticspeak) | diplomatize | Converts direct or blunt text into polite, tactful diplomatic language. |
| [ConvertTo-LMStudioFunctionDefinition](https://github.com/genXdev/GenXdev.AI/tree/main#convertto-lmstudiofunctiondefinition) | &nbsp; | Converts PowerShell functions to LMStudio function definitions. |
| [CreateComfySDXLWorkflow](https://github.com/genXdev/GenXdev.AI/tree/main#createcomfysdxlworkflow) | &nbsp; | Creates comprehensive ComfyUI SDXL workflow configuration supporting all parameters |
| [CreateComfyUniversalWorkflow](https://github.com/genXdev/GenXdev.AI/tree/main#createcomfyuniversalworkflow) | &nbsp; | Creates comprehensive ComfyUI workflow configuration supporting all parameters |
| [DownloadComfyResults](https://github.com/genXdev/GenXdev.AI/tree/main#downloadcomfyresults) | &nbsp; | Downloads generated results from ComfyUI server with file information |
| [EnsureComfyUI](https://github.com/genXdev/GenXdev.AI/tree/main#ensurecomfyui) | &nbsp; | Ensures ComfyUI is installed and running with optional window positioning. |
| [EnsureComfyUIModel](https://github.com/genXdev/GenXdev.AI/tree/main#ensurecomfyuimodel) | &nbsp; | Ensures specified ComfyUI models are available locally with automatic download |
| [EnsureDeepStack](https://github.com/genXdev/GenXdev.AI/tree/main#ensuredeepstack) | &nbsp; | Ensures DeepStack face recognition service is installed and running. |
| [EnsureGithubCLIInstalled](https://github.com/genXdev/GenXdev.AI/tree/main#ensuregithubcliinstalled) | &nbsp; | Ensures GitHub CLI is properly installed and configured on the system. |
| [EnsureHuggingFace](https://github.com/genXdev/GenXdev.AI/tree/main#ensurehuggingface) | &nbsp; | Ensures the Hugging Face CLI is installed and functional. |
| [EnsureLMStudio](https://github.com/genXdev/GenXdev.AI/tree/main#ensurelmstudio) | &nbsp; | Ensures LM Studio is properly initialized with the specified model. |
| [EnsurePaintNet](https://github.com/genXdev/GenXdev.AI/tree/main#ensurepaintnet) | &nbsp; | Ensures Paint.NET is properly installed and accessible on the system. |
| [EnsurePip](https://github.com/genXdev/GenXdev.AI/tree/main#ensurepip) | &nbsp; | Ensures pip is installed and functional for the specified Python installation. |
| [EnsurePython](https://github.com/genXdev/GenXdev.AI/tree/main#ensurepython) | &nbsp; | Ensures Python is installed and available in the system PATH. |
| [EnsureWinMergeInstalled](https://github.com/genXdev/GenXdev.AI/tree/main#ensurewinmergeinstalled) | &nbsp; | Ensures WinMerge is installed and available for file comparison operations. |
| [Export-ImageIndex](https://github.com/genXdev/GenXdev.AI/tree/main#export-imageindex) | indeximages | Initializes and populates the SQLite database by discovering images directly. |
| [Find-Image](https://github.com/genXdev/GenXdev.AI/tree/main#find-image) | findimages, li | &nbsp; |
| [Find-IndexedImage](https://github.com/genXdev/GenXdev.AI/tree/main#find-indexedimage) | findindexedimages, lii | Searches for images using an optimized SQLite database with fast indexed lookups. |
| [GenerateMasonryLayoutHtml](https://github.com/genXdev/GenXdev.AI/tree/main#generatemasonrylayouthtml) | &nbsp; | Generates a responsive masonry layout HTML gallery from image data. |
| [Get-AIDefaultLLMSettings](https://github.com/genXdev/GenXdev.AI/tree/main#get-aidefaultllmsettings) | &nbsp; | Gets all available default LLM settings configurations for AI operations in GenXdev.AI. |
| [Get-AIImageCollection](https://github.com/genXdev/GenXdev.AI/tree/main#get-aiimagecollection) | getimgdirs | Gets the configured directories for image files used in GenXdev.AI operations. |
| [Get-AIKnownFacesRootpath](https://github.com/genXdev/GenXdev.AI/tree/main#get-aiknownfacesrootpath) | &nbsp; | &nbsp; |
| [Get-AILLMSettings](https://github.com/genXdev/GenXdev.AI/tree/main#get-aillmsettings) | &nbsp; | Gets the LLM settings for AI operations in GenXdev.AI. |
| [Get-AIMetaLanguage](https://github.com/genXdev/GenXdev.AI/tree/main#get-aimetalanguage) | getimgmetalang | Gets the configured default language for image metadata operations. |
| [Get-ComfyUIModelPath](https://github.com/genXdev/GenXdev.AI/tree/main#get-comfyuimodelpath) | &nbsp; | Gets the correct ComfyUI models directory path for the current installation |
| [Get-CpuCore](https://github.com/genXdev/GenXdev.AI/tree/main#get-cpucore) | &nbsp; | Calculates and returns the total number of logical CPU cores in the system. |
| [Get-Fallacy](https://github.com/genXdev/GenXdev.AI/tree/main#get-fallacy) | dispicetext | Analyzes text to identify logical fallacies using AI-powered detection. |
| [Get-HasCapableGpu](https://github.com/genXdev/GenXdev.AI/tree/main#get-hascapablegpu) | &nbsp; | Determines if a CUDA-capable GPU with sufficient memory is present. |
| [Get-ImageDetectedFaces](https://github.com/genXdev/GenXdev.AI/tree/main#get-imagedetectedfaces) | &nbsp; | &nbsp; |
| [Get-ImageDetectedObjects](https://github.com/genXdev/GenXdev.AI/tree/main#get-imagedetectedobjects) | &nbsp; | Detects and classifies objects in an uploaded image using DeepStack. |
| [Get-ImageDetectedScenes](https://github.com/genXdev/GenXdev.AI/tree/main#get-imagedetectedscenes) | &nbsp; | Classifies an image into one of 365 scene categories using DeepStack. |
| [Get-ImageIndexPath](https://github.com/genXdev/GenXdev.AI/tree/main#get-imageindexpath) | &nbsp; | Returns the path to the image database, initializing or rebuilding it if needed. |
| [Get-ImageIndexStats](https://github.com/genXdev/GenXdev.AI/tree/main#get-imageindexstats) | getimagedbstats, gids | Retrieves comprehensive statistics and information about the image database. |
| [Get-LMStudioLoadedModelList](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudioloadedmodellist) | &nbsp; | Retrieves the list of currently loaded models from LM Studio. |
| [Get-LMStudioModelList](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiomodellist) | &nbsp; | Retrieves a list of installed LM Studio models. |
| [Get-LMStudioPaths](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiopaths) | &nbsp; | Retrieves file paths for LM Studio executables. |
| [Get-LMStudioTextEmbedding](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiotextembedding) | &nbsp; | Gets text embeddings from LM Studio model. |
| [Get-LMStudioWindow](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiowindow) | lmstudiowindow, setlmstudiowindow | Gets a window helper for the LM Studio application. |
| [Get-NumberOfCpuCores](https://github.com/genXdev/GenXdev.AI/tree/main#get-numberofcpucores) | &nbsp; | Calculates and returns the total number of logical CPU cores in the system. |
| [Get-RegisteredFaces](https://github.com/genXdev/GenXdev.AI/tree/main#get-registeredfaces) | &nbsp; | Retrieves a list of all registered face identifiers from DeepStack. |
| [Get-ScriptExecutionErrorFixPrompt](https://github.com/genXdev/GenXdev.AI/tree/main#get-scriptexecutionerrorfixprompt) | getfixprompt | Captures error messages from various streams and uses LLM to suggest fixes. |
| [Get-SimularMovieTitles](https://github.com/genXdev/GenXdev.AI/tree/main#get-simularmovietitles) | &nbsp; | Finds similar movie titles based on common properties. |
| [Get-TextTranslation](https://github.com/genXdev/GenXdev.AI/tree/main#get-texttranslation) | translate | Translates text to another language using AI. |
| [Get-VectorSimilarity](https://github.com/genXdev/GenXdev.AI/tree/main#get-vectorsimilarity) | &nbsp; | &nbsp; |
| [Initialize-LMStudioModel](https://github.com/genXdev/GenXdev.AI/tree/main#initialize-lmstudiomodel) | initlmstudio | Initializes and loads an AI model in LM Studio. |
| [Install-LMStudioApplication](https://github.com/genXdev/GenXdev.AI/tree/main#install-lmstudioapplication) | &nbsp; | Installs LM Studio application using WinGet package manager. |
| [Invoke-AIPowershellCommand](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-aipowershellcommand) | hint | Converts AI command suggestions to JSON format for processing. |
| [Invoke-ComfyUIImageGeneration](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-comfyuiimagegeneration) | generateimage | &nbsp; |
| [Invoke-CommandFromToolCall](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-commandfromtoolcall) | &nbsp; | Executes a tool call function with validation and parameter filtering. |
| [Invoke-HuggingFaceCli](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-huggingfacecli) | &nbsp; | Invokes the Hugging Face CLI with the specified arguments. |
| [Invoke-ImageEnhancement](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imageenhancement) | enhanceimage | Enhances an image by enlarging it 4X while improving quality using DeepStack. |
| [Invoke-ImageFacesUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagefacesupdate) | imagepeopledetection | Updates face recognition metadata for image files in a specified directory. |
| [Invoke-ImageKeywordUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagekeywordupdate) | imagekeywordgeneration | Updates image metadata with AI-generated descriptions and keywords. |
| [Invoke-ImageMetadataUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagemetadataupdate) | imagepropdetection | Updates EXIF metadata for images in a directory. |
| [Invoke-ImageObjectsUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imageobjectsupdate) | imageobjectdetection | Updates object detection metadata for image files in a specified directory. |
| [Invoke-ImageScenesUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagescenesupdate) | imagescenedetection | Updates scene classification metadata for image files in a specified directory. |
| [Invoke-LLMBooleanEvaluation](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmbooleanevaluation) | equalstrue | Evaluates a statement using AI to determine if it's true or false. |
| [Invoke-LLMQuery](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmquery) | llm, qllm | &nbsp; |
| [Invoke-LLMStringListEvaluation](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmstringlistevaluation) | getlist, getstring | &nbsp; |
| [Invoke-LLMTextTransformation](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmtexttransformation) | spellcheck | Transforms text using AI-powered processing. |
| [Invoke-QueryImageContent](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-queryimagecontent) | &nbsp; | Analyzes image content using AI vision capabilities through the LM-Studio API. |
| [Invoke-WinMerge](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-winmerge) | &nbsp; | Launches WinMerge to compare two files side by side. |
| [New-LLMAudioChat](https://github.com/genXdev/GenXdev.AI/tree/main#new-llmaudiochat) | llmaudiochat | Creates an interactive audio chat session with an LLM model. |
| [New-LLMTextChat](https://github.com/genXdev/GenXdev.AI/tree/main#new-llmtextchat) | llmchat | Starts an interactive text chat session with AI capabilities. |
| [QueueComfyWorkflow](https://github.com/genXdev/GenXdev.AI/tree/main#queuecomfyworkflow) | &nbsp; | Submits workflow to ComfyUI processing queue for execution. |
| [Register-AllFaces](https://github.com/genXdev/GenXdev.AI/tree/main#register-allfaces) | UpdateFaces | Updates all face recognition profiles from image files in the faces directory. |
| [Register-Face](https://github.com/genXdev/GenXdev.AI/tree/main#register-face) | &nbsp; | Registers a new face with the DeepStack face recognition API. |
| [Remove-ImageDirectories](https://github.com/genXdev/GenXdev.AI/tree/main#remove-imagedirectories) | removeimgdir | Removes directories from the configured image directories for GenXdev.AI operations. |
| [Remove-ImageMetaData](https://github.com/genXdev/GenXdev.AI/tree/main#remove-imagemetadata) | removeimagedata | Removes image metadata files from image directories. |
| [ResizeComfyInputImage](https://github.com/genXdev/GenXdev.AI/tree/main#resizecomfyinputimage) | &nbsp; | Resizes input image while preserving aspect ratio for optimal processing. |
| [Save-FoundImageFaces](https://github.com/genXdev/GenXdev.AI/tree/main#save-foundimagefaces) | saveimagefaces | Saves cropped face images from indexed image search results. |
| [Save-FoundImageObjects](https://github.com/genXdev/GenXdev.AI/tree/main#save-foundimageobjects) | saveimageObjects | Saves cropped object images from indexed image search results to files. |
| [Save-Transcriptions](https://github.com/genXdev/GenXdev.AI/tree/main#save-transcriptions) | &nbsp; | Generates subtitle files for audio and video files using OpenAI Whisper. |
| [Set-AIImageCollection](https://github.com/genXdev/GenXdev.AI/tree/main#set-aiimagecollection) | &nbsp; | &nbsp; |
| [Set-AIKnownFacesRootpath](https://github.com/genXdev/GenXdev.AI/tree/main#set-aiknownfacesrootpath) | &nbsp; | Sets the directory for face image files used in GenXdev.AI operations. |
| [Set-AILLMSettings](https://github.com/genXdev/GenXdev.AI/tree/main#set-aillmsettings) | &nbsp; | Sets the LLM settings for AI operations in GenXdev.AI. |
| [Set-AIMetaLanguage](https://github.com/genXdev/GenXdev.AI/tree/main#set-aimetalanguage) | &nbsp; | &nbsp; |
| [Set-ComfyUIBackgroundImage](https://github.com/genXdev/GenXdev.AI/tree/main#set-comfyuibackgroundimage) | &nbsp; | Sets or clears the background image for ComfyUI's canvas interface |
| [Set-ComfyUIModelPath](https://github.com/genXdev/GenXdev.AI/tree/main#set-comfyuimodelpath) | &nbsp; | Adds a custom model path to ComfyUI's extra_model_paths.yaml configuration |
| [Set-GenXdevAICommandNotFoundAction](https://github.com/genXdev/GenXdev.AI/tree/main#set-genxdevaicommandnotfoundaction) | &nbsp; | Sets up custom command not found handling with AI assistance. |
| [Set-ImageIndexPath](https://github.com/genXdev/GenXdev.AI/tree/main#set-imageindexpath) | &nbsp; | Sets the default database file path for image operations in GenXdev.AI. |
| [Set-WindowsWallpaperEx](https://github.com/genXdev/GenXdev.AI/tree/main#set-windowswallpaperex) | nextwallpaper | Sets a random wallpaper from a specified directory or search criteria. |
| [SetComfyUIProcessPriority](https://github.com/genXdev/GenXdev.AI/tree/main#setcomfyuiprocesspriority) | &nbsp; | Sets ComfyUI processes to IDLE priority for CPU mode processing optimization. |
| [Show-FoundImagesInBrowser](https://github.com/genXdev/GenXdev.AI/tree/main#show-foundimagesinbrowser) | showfoundimages | Displays image search results in a masonry layout web gallery. |
| [Show-GenXdevScriptErrorFixInIde](https://github.com/genXdev/GenXdev.AI/tree/main#show-genxdevscripterrorfixinide) | letsfixthis | Executes a script block and analyzes errors using AI to generate fixes in IDE. |
| [Start-AudioTranscription](https://github.com/genXdev/GenXdev.AI/tree/main#start-audiotranscription) | transcribe, transcribefile | Transcribes an audio file, video file, or a recording device to text |
| [Start-GenXdevMCPServer](https://github.com/genXdev/GenXdev.AI/tree/main#start-genxdevmcpserver) | &nbsp; | Starts the GenXdev MCP server that exposes PowerShell cmdlets as tools. |
| [Start-LMStudioApplication](https://github.com/genXdev/GenXdev.AI/tree/main#start-lmstudioapplication) | &nbsp; | Starts the LM Studio application if it's not already running. |
| [Stop-ComfyUI](https://github.com/genXdev/GenXdev.AI/tree/main#stop-comfyui) | &nbsp; | Terminates all running ComfyUI processes and releases associated resources. |
| [Test-ComfyUIQueueEmpty](https://github.com/genXdev/GenXdev.AI/tree/main#test-comfyuiqueueempty) | &nbsp; | Checks if the ComfyUI processing queue is empty |
| [Test-DeepLinkImageFile](https://github.com/genXdev/GenXdev.AI/tree/main#test-deeplinkimagefile) | &nbsp; | Tests if the specified file path is a valid image file with a supported format. |
| [Test-LMStudioInstallation](https://github.com/genXdev/GenXdev.AI/tree/main#test-lmstudioinstallation) | &nbsp; | Tests if LMStudio is installed and accessible on the system. |
| [Test-LMStudioProcess](https://github.com/genXdev/GenXdev.AI/tree/main#test-lmstudioprocess) | &nbsp; | Tests if LM Studio process is running and configures its window state. |
| [Unregister-AllFaces](https://github.com/genXdev/GenXdev.AI/tree/main#unregister-allfaces) | &nbsp; | Removes all registered faces from the DeepStack face recognition system. |
| [Unregister-Face](https://github.com/genXdev/GenXdev.AI/tree/main#unregister-face) | &nbsp; | Deletes a registered face by its identifier from DeepStack. |
| [Update-AllImageMetaData](https://github.com/genXdev/GenXdev.AI/tree/main#update-allimagemetadata) | updateallimages | &nbsp; |
| [UploadComfyImage](https://github.com/genXdev/GenXdev.AI/tree/main#uploadcomfyimage) | &nbsp; | Uploads image file to ComfyUI server for processing workflow integration. |
| [WaitForComfyCompletion](https://github.com/genXdev/GenXdev.AI/tree/main#waitforcomfycompletion) | &nbsp; | Waits for ComfyUI workflow completion with progress monitoring |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.AI/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.AI.LMStudio

**A Windows PowerShell module for local AI related operations**

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [Add-EmoticonsToText](https://github.com/genXdev/GenXdev.AI/tree/main#add-emoticonstotext) | emojify | Enhances text by adding contextually appropriate emoticons using AI. |
| [Add-GenXdevMCPServerToLMStudio](https://github.com/genXdev/GenXdev.AI/tree/main#add-genxdevmcpservertolmstudio) | &nbsp; | Adds the GenXdev MCP server to LM Studio using a deeplink configuration. |
| [Add-ImageDirectories](https://github.com/genXdev/GenXdev.AI/tree/main#add-imagedirectories) | addimgdir | Adds directories to the configured image directories for GenXdev.AI operations. |
| [Approve-NewTextFileContent](https://github.com/genXdev/GenXdev.AI/tree/main#approve-newtextfilecontent) | &nbsp; | Interactive file content comparison and approval using WinMerge. |
| [Compare-ImageFaces](https://github.com/genXdev/GenXdev.AI/tree/main#compare-imagefaces) | comparefaces | Processes the face match result from DeepStack API. |
| [Convert-DotNetTypeToLLMType](https://github.com/genXdev/GenXdev.AI/tree/main#convert-dotnettypetollmtype) | &nbsp; | Converts .NET type names to LLM (Language Model) type names. |
| [ConvertComfyImageFormat](https://github.com/genXdev/GenXdev.AI/tree/main#convertcomfyimageformat) | &nbsp; | Converts image file format while preserving maximum quality. |
| [ConvertFrom-CorporateSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertfrom-corporatespeak) | uncorporatize | Converts polite, professional corporate speak into direct, clear language using AI. |
| [ConvertFrom-DiplomaticSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertfrom-diplomaticspeak) | undiplomatize | &nbsp; |
| [ConvertTo-CorporateSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertto-corporatespeak) | corporatize | Converts direct or blunt text into polite, professional corporate speak using AI. |
| [ConvertTo-DiplomaticSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertto-diplomaticspeak) | diplomatize | Converts direct or blunt text into polite, tactful diplomatic language. |
| [ConvertTo-LMStudioFunctionDefinition](https://github.com/genXdev/GenXdev.AI/tree/main#convertto-lmstudiofunctiondefinition) | &nbsp; | Converts PowerShell functions to LMStudio function definitions. |
| [CreateComfySDXLWorkflow](https://github.com/genXdev/GenXdev.AI/tree/main#createcomfysdxlworkflow) | &nbsp; | Creates comprehensive ComfyUI SDXL workflow configuration supporting all parameters |
| [CreateComfyUniversalWorkflow](https://github.com/genXdev/GenXdev.AI/tree/main#createcomfyuniversalworkflow) | &nbsp; | Creates comprehensive ComfyUI workflow configuration supporting all parameters |
| [DownloadComfyResults](https://github.com/genXdev/GenXdev.AI/tree/main#downloadcomfyresults) | &nbsp; | Downloads generated results from ComfyUI server with file information |
| [EnsureComfyUI](https://github.com/genXdev/GenXdev.AI/tree/main#ensurecomfyui) | &nbsp; | Ensures ComfyUI is installed and running with optional window positioning. |
| [EnsureComfyUIModel](https://github.com/genXdev/GenXdev.AI/tree/main#ensurecomfyuimodel) | &nbsp; | Ensures specified ComfyUI models are available locally with automatic download |
| [EnsureDeepStack](https://github.com/genXdev/GenXdev.AI/tree/main#ensuredeepstack) | &nbsp; | Ensures DeepStack face recognition service is installed and running. |
| [EnsureGithubCLIInstalled](https://github.com/genXdev/GenXdev.AI/tree/main#ensuregithubcliinstalled) | &nbsp; | Ensures GitHub CLI is properly installed and configured on the system. |
| [EnsureHuggingFace](https://github.com/genXdev/GenXdev.AI/tree/main#ensurehuggingface) | &nbsp; | Ensures the Hugging Face CLI is installed and functional. |
| [EnsureLMStudio](https://github.com/genXdev/GenXdev.AI/tree/main#ensurelmstudio) | &nbsp; | Ensures LM Studio is properly initialized with the specified model. |
| [EnsurePaintNet](https://github.com/genXdev/GenXdev.AI/tree/main#ensurepaintnet) | &nbsp; | Ensures Paint.NET is properly installed and accessible on the system. |
| [EnsurePip](https://github.com/genXdev/GenXdev.AI/tree/main#ensurepip) | &nbsp; | Ensures pip is installed and functional for the specified Python installation. |
| [EnsurePython](https://github.com/genXdev/GenXdev.AI/tree/main#ensurepython) | &nbsp; | Ensures Python is installed and available in the system PATH. |
| [EnsureWinMergeInstalled](https://github.com/genXdev/GenXdev.AI/tree/main#ensurewinmergeinstalled) | &nbsp; | Ensures WinMerge is installed and available for file comparison operations. |
| [Export-ImageIndex](https://github.com/genXdev/GenXdev.AI/tree/main#export-imageindex) | indeximages | Initializes and populates the SQLite database by discovering images directly. |
| [Find-Image](https://github.com/genXdev/GenXdev.AI/tree/main#find-image) | findimages, li | &nbsp; |
| [Find-IndexedImage](https://github.com/genXdev/GenXdev.AI/tree/main#find-indexedimage) | findindexedimages, lii | Searches for images using an optimized SQLite database with fast indexed lookups. |
| [GenerateMasonryLayoutHtml](https://github.com/genXdev/GenXdev.AI/tree/main#generatemasonrylayouthtml) | &nbsp; | Generates a responsive masonry layout HTML gallery from image data. |
| [Get-AIDefaultLLMSettings](https://github.com/genXdev/GenXdev.AI/tree/main#get-aidefaultllmsettings) | &nbsp; | Gets all available default LLM settings configurations for AI operations in GenXdev.AI. |
| [Get-AIImageCollection](https://github.com/genXdev/GenXdev.AI/tree/main#get-aiimagecollection) | getimgdirs | Gets the configured directories for image files used in GenXdev.AI operations. |
| [Get-AIKnownFacesRootpath](https://github.com/genXdev/GenXdev.AI/tree/main#get-aiknownfacesrootpath) | &nbsp; | &nbsp; |
| [Get-AILLMSettings](https://github.com/genXdev/GenXdev.AI/tree/main#get-aillmsettings) | &nbsp; | Gets the LLM settings for AI operations in GenXdev.AI. |
| [Get-AIMetaLanguage](https://github.com/genXdev/GenXdev.AI/tree/main#get-aimetalanguage) | getimgmetalang | Gets the configured default language for image metadata operations. |
| [Get-ComfyUIModelPath](https://github.com/genXdev/GenXdev.AI/tree/main#get-comfyuimodelpath) | &nbsp; | Gets the correct ComfyUI models directory path for the current installation |
| [Get-CpuCore](https://github.com/genXdev/GenXdev.AI/tree/main#get-cpucore) | &nbsp; | Calculates and returns the total number of logical CPU cores in the system. |
| [Get-Fallacy](https://github.com/genXdev/GenXdev.AI/tree/main#get-fallacy) | dispicetext | Analyzes text to identify logical fallacies using AI-powered detection. |
| [Get-HasCapableGpu](https://github.com/genXdev/GenXdev.AI/tree/main#get-hascapablegpu) | &nbsp; | Determines if a CUDA-capable GPU with sufficient memory is present. |
| [Get-ImageDetectedFaces](https://github.com/genXdev/GenXdev.AI/tree/main#get-imagedetectedfaces) | &nbsp; | &nbsp; |
| [Get-ImageDetectedObjects](https://github.com/genXdev/GenXdev.AI/tree/main#get-imagedetectedobjects) | &nbsp; | Detects and classifies objects in an uploaded image using DeepStack. |
| [Get-ImageDetectedScenes](https://github.com/genXdev/GenXdev.AI/tree/main#get-imagedetectedscenes) | &nbsp; | Classifies an image into one of 365 scene categories using DeepStack. |
| [Get-ImageIndexPath](https://github.com/genXdev/GenXdev.AI/tree/main#get-imageindexpath) | &nbsp; | Returns the path to the image database, initializing or rebuilding it if needed. |
| [Get-ImageIndexStats](https://github.com/genXdev/GenXdev.AI/tree/main#get-imageindexstats) | getimagedbstats, gids | Retrieves comprehensive statistics and information about the image database. |
| [Get-LMStudioLoadedModelList](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudioloadedmodellist) | &nbsp; | Retrieves the list of currently loaded models from LM Studio. |
| [Get-LMStudioModelList](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiomodellist) | &nbsp; | Retrieves a list of installed LM Studio models. |
| [Get-LMStudioPaths](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiopaths) | &nbsp; | Retrieves file paths for LM Studio executables. |
| [Get-LMStudioTextEmbedding](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiotextembedding) | &nbsp; | Gets text embeddings from LM Studio model. |
| [Get-LMStudioWindow](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiowindow) | lmstudiowindow, setlmstudiowindow | Gets a window helper for the LM Studio application. |
| [Get-NumberOfCpuCores](https://github.com/genXdev/GenXdev.AI/tree/main#get-numberofcpucores) | &nbsp; | Calculates and returns the total number of logical CPU cores in the system. |
| [Get-RegisteredFaces](https://github.com/genXdev/GenXdev.AI/tree/main#get-registeredfaces) | &nbsp; | Retrieves a list of all registered face identifiers from DeepStack. |
| [Get-ScriptExecutionErrorFixPrompt](https://github.com/genXdev/GenXdev.AI/tree/main#get-scriptexecutionerrorfixprompt) | getfixprompt | Captures error messages from various streams and uses LLM to suggest fixes. |
| [Get-SimularMovieTitles](https://github.com/genXdev/GenXdev.AI/tree/main#get-simularmovietitles) | &nbsp; | Finds similar movie titles based on common properties. |
| [Get-TextTranslation](https://github.com/genXdev/GenXdev.AI/tree/main#get-texttranslation) | translate | Translates text to another language using AI. |
| [Get-VectorSimilarity](https://github.com/genXdev/GenXdev.AI/tree/main#get-vectorsimilarity) | &nbsp; | &nbsp; |
| [Initialize-LMStudioModel](https://github.com/genXdev/GenXdev.AI/tree/main#initialize-lmstudiomodel) | initlmstudio | Initializes and loads an AI model in LM Studio. |
| [Install-LMStudioApplication](https://github.com/genXdev/GenXdev.AI/tree/main#install-lmstudioapplication) | &nbsp; | Installs LM Studio application using WinGet package manager. |
| [Invoke-AIPowershellCommand](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-aipowershellcommand) | hint | Converts AI command suggestions to JSON format for processing. |
| [Invoke-ComfyUIImageGeneration](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-comfyuiimagegeneration) | generateimage | &nbsp; |
| [Invoke-CommandFromToolCall](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-commandfromtoolcall) | &nbsp; | Executes a tool call function with validation and parameter filtering. |
| [Invoke-HuggingFaceCli](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-huggingfacecli) | &nbsp; | Invokes the Hugging Face CLI with the specified arguments. |
| [Invoke-ImageEnhancement](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imageenhancement) | enhanceimage | Enhances an image by enlarging it 4X while improving quality using DeepStack. |
| [Invoke-ImageFacesUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagefacesupdate) | imagepeopledetection | Updates face recognition metadata for image files in a specified directory. |
| [Invoke-ImageKeywordUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagekeywordupdate) | imagekeywordgeneration | Updates image metadata with AI-generated descriptions and keywords. |
| [Invoke-ImageMetadataUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagemetadataupdate) | imagepropdetection | Updates EXIF metadata for images in a directory. |
| [Invoke-ImageObjectsUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imageobjectsupdate) | imageobjectdetection | Updates object detection metadata for image files in a specified directory. |
| [Invoke-ImageScenesUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagescenesupdate) | imagescenedetection | Updates scene classification metadata for image files in a specified directory. |
| [Invoke-LLMBooleanEvaluation](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmbooleanevaluation) | equalstrue | Evaluates a statement using AI to determine if it's true or false. |
| [Invoke-LLMQuery](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmquery) | llm, qllm | &nbsp; |
| [Invoke-LLMStringListEvaluation](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmstringlistevaluation) | getlist, getstring | &nbsp; |
| [Invoke-LLMTextTransformation](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmtexttransformation) | spellcheck | Transforms text using AI-powered processing. |
| [Invoke-QueryImageContent](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-queryimagecontent) | &nbsp; | Analyzes image content using AI vision capabilities through the LM-Studio API. |
| [Invoke-WinMerge](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-winmerge) | &nbsp; | Launches WinMerge to compare two files side by side. |
| [New-LLMAudioChat](https://github.com/genXdev/GenXdev.AI/tree/main#new-llmaudiochat) | llmaudiochat | Creates an interactive audio chat session with an LLM model. |
| [New-LLMTextChat](https://github.com/genXdev/GenXdev.AI/tree/main#new-llmtextchat) | llmchat | Starts an interactive text chat session with AI capabilities. |
| [QueueComfyWorkflow](https://github.com/genXdev/GenXdev.AI/tree/main#queuecomfyworkflow) | &nbsp; | Submits workflow to ComfyUI processing queue for execution. |
| [Register-AllFaces](https://github.com/genXdev/GenXdev.AI/tree/main#register-allfaces) | UpdateFaces | Updates all face recognition profiles from image files in the faces directory. |
| [Register-Face](https://github.com/genXdev/GenXdev.AI/tree/main#register-face) | &nbsp; | Registers a new face with the DeepStack face recognition API. |
| [Remove-ImageDirectories](https://github.com/genXdev/GenXdev.AI/tree/main#remove-imagedirectories) | removeimgdir | Removes directories from the configured image directories for GenXdev.AI operations. |
| [Remove-ImageMetaData](https://github.com/genXdev/GenXdev.AI/tree/main#remove-imagemetadata) | removeimagedata | Removes image metadata files from image directories. |
| [ResizeComfyInputImage](https://github.com/genXdev/GenXdev.AI/tree/main#resizecomfyinputimage) | &nbsp; | Resizes input image while preserving aspect ratio for optimal processing. |
| [Save-FoundImageFaces](https://github.com/genXdev/GenXdev.AI/tree/main#save-foundimagefaces) | saveimagefaces | Saves cropped face images from indexed image search results. |
| [Save-FoundImageObjects](https://github.com/genXdev/GenXdev.AI/tree/main#save-foundimageobjects) | saveimageObjects | Saves cropped object images from indexed image search results to files. |
| [Save-Transcriptions](https://github.com/genXdev/GenXdev.AI/tree/main#save-transcriptions) | &nbsp; | Generates subtitle files for audio and video files using OpenAI Whisper. |
| [Set-AIImageCollection](https://github.com/genXdev/GenXdev.AI/tree/main#set-aiimagecollection) | &nbsp; | &nbsp; |
| [Set-AIKnownFacesRootpath](https://github.com/genXdev/GenXdev.AI/tree/main#set-aiknownfacesrootpath) | &nbsp; | Sets the directory for face image files used in GenXdev.AI operations. |
| [Set-AILLMSettings](https://github.com/genXdev/GenXdev.AI/tree/main#set-aillmsettings) | &nbsp; | Sets the LLM settings for AI operations in GenXdev.AI. |
| [Set-AIMetaLanguage](https://github.com/genXdev/GenXdev.AI/tree/main#set-aimetalanguage) | &nbsp; | &nbsp; |
| [Set-ComfyUIBackgroundImage](https://github.com/genXdev/GenXdev.AI/tree/main#set-comfyuibackgroundimage) | &nbsp; | Sets or clears the background image for ComfyUI's canvas interface |
| [Set-ComfyUIModelPath](https://github.com/genXdev/GenXdev.AI/tree/main#set-comfyuimodelpath) | &nbsp; | Adds a custom model path to ComfyUI's extra_model_paths.yaml configuration |
| [Set-GenXdevAICommandNotFoundAction](https://github.com/genXdev/GenXdev.AI/tree/main#set-genxdevaicommandnotfoundaction) | &nbsp; | Sets up custom command not found handling with AI assistance. |
| [Set-ImageIndexPath](https://github.com/genXdev/GenXdev.AI/tree/main#set-imageindexpath) | &nbsp; | Sets the default database file path for image operations in GenXdev.AI. |
| [Set-WindowsWallpaperEx](https://github.com/genXdev/GenXdev.AI/tree/main#set-windowswallpaperex) | nextwallpaper | Sets a random wallpaper from a specified directory or search criteria. |
| [SetComfyUIProcessPriority](https://github.com/genXdev/GenXdev.AI/tree/main#setcomfyuiprocesspriority) | &nbsp; | Sets ComfyUI processes to IDLE priority for CPU mode processing optimization. |
| [Show-FoundImagesInBrowser](https://github.com/genXdev/GenXdev.AI/tree/main#show-foundimagesinbrowser) | showfoundimages | Displays image search results in a masonry layout web gallery. |
| [Show-GenXdevScriptErrorFixInIde](https://github.com/genXdev/GenXdev.AI/tree/main#show-genxdevscripterrorfixinide) | letsfixthis | Executes a script block and analyzes errors using AI to generate fixes in IDE. |
| [Start-AudioTranscription](https://github.com/genXdev/GenXdev.AI/tree/main#start-audiotranscription) | transcribe, transcribefile | Transcribes an audio file, video file, or a recording device to text |
| [Start-GenXdevMCPServer](https://github.com/genXdev/GenXdev.AI/tree/main#start-genxdevmcpserver) | &nbsp; | Starts the GenXdev MCP server that exposes PowerShell cmdlets as tools. |
| [Start-LMStudioApplication](https://github.com/genXdev/GenXdev.AI/tree/main#start-lmstudioapplication) | &nbsp; | Starts the LM Studio application if it's not already running. |
| [Stop-ComfyUI](https://github.com/genXdev/GenXdev.AI/tree/main#stop-comfyui) | &nbsp; | Terminates all running ComfyUI processes and releases associated resources. |
| [Test-ComfyUIQueueEmpty](https://github.com/genXdev/GenXdev.AI/tree/main#test-comfyuiqueueempty) | &nbsp; | Checks if the ComfyUI processing queue is empty |
| [Test-DeepLinkImageFile](https://github.com/genXdev/GenXdev.AI/tree/main#test-deeplinkimagefile) | &nbsp; | Tests if the specified file path is a valid image file with a supported format. |
| [Test-LMStudioInstallation](https://github.com/genXdev/GenXdev.AI/tree/main#test-lmstudioinstallation) | &nbsp; | Tests if LMStudio is installed and accessible on the system. |
| [Test-LMStudioProcess](https://github.com/genXdev/GenXdev.AI/tree/main#test-lmstudioprocess) | &nbsp; | Tests if LM Studio process is running and configures its window state. |
| [Unregister-AllFaces](https://github.com/genXdev/GenXdev.AI/tree/main#unregister-allfaces) | &nbsp; | Removes all registered faces from the DeepStack face recognition system. |
| [Unregister-Face](https://github.com/genXdev/GenXdev.AI/tree/main#unregister-face) | &nbsp; | Deletes a registered face by its identifier from DeepStack. |
| [Update-AllImageMetaData](https://github.com/genXdev/GenXdev.AI/tree/main#update-allimagemetadata) | updateallimages | &nbsp; |
| [UploadComfyImage](https://github.com/genXdev/GenXdev.AI/tree/main#uploadcomfyimage) | &nbsp; | Uploads image file to ComfyUI server for processing workflow integration. |
| [WaitForComfyCompletion](https://github.com/genXdev/GenXdev.AI/tree/main#waitforcomfycompletion) | &nbsp; | Waits for ComfyUI workflow completion with progress monitoring |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.AI/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.AI.Queries

**A Windows PowerShell module for local AI related operations**

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [Add-EmoticonsToText](https://github.com/genXdev/GenXdev.AI/tree/main#add-emoticonstotext) | emojify | Enhances text by adding contextually appropriate emoticons using AI. |
| [Add-GenXdevMCPServerToLMStudio](https://github.com/genXdev/GenXdev.AI/tree/main#add-genxdevmcpservertolmstudio) | &nbsp; | Adds the GenXdev MCP server to LM Studio using a deeplink configuration. |
| [Add-ImageDirectories](https://github.com/genXdev/GenXdev.AI/tree/main#add-imagedirectories) | addimgdir | Adds directories to the configured image directories for GenXdev.AI operations. |
| [Approve-NewTextFileContent](https://github.com/genXdev/GenXdev.AI/tree/main#approve-newtextfilecontent) | &nbsp; | Interactive file content comparison and approval using WinMerge. |
| [Compare-ImageFaces](https://github.com/genXdev/GenXdev.AI/tree/main#compare-imagefaces) | comparefaces | Processes the face match result from DeepStack API. |
| [Convert-DotNetTypeToLLMType](https://github.com/genXdev/GenXdev.AI/tree/main#convert-dotnettypetollmtype) | &nbsp; | Converts .NET type names to LLM (Language Model) type names. |
| [ConvertComfyImageFormat](https://github.com/genXdev/GenXdev.AI/tree/main#convertcomfyimageformat) | &nbsp; | Converts image file format while preserving maximum quality. |
| [ConvertFrom-CorporateSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertfrom-corporatespeak) | uncorporatize | Converts polite, professional corporate speak into direct, clear language using AI. |
| [ConvertFrom-DiplomaticSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertfrom-diplomaticspeak) | undiplomatize | &nbsp; |
| [ConvertTo-CorporateSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertto-corporatespeak) | corporatize | Converts direct or blunt text into polite, professional corporate speak using AI. |
| [ConvertTo-DiplomaticSpeak](https://github.com/genXdev/GenXdev.AI/tree/main#convertto-diplomaticspeak) | diplomatize | Converts direct or blunt text into polite, tactful diplomatic language. |
| [ConvertTo-LMStudioFunctionDefinition](https://github.com/genXdev/GenXdev.AI/tree/main#convertto-lmstudiofunctiondefinition) | &nbsp; | Converts PowerShell functions to LMStudio function definitions. |
| [CreateComfySDXLWorkflow](https://github.com/genXdev/GenXdev.AI/tree/main#createcomfysdxlworkflow) | &nbsp; | Creates comprehensive ComfyUI SDXL workflow configuration supporting all parameters |
| [CreateComfyUniversalWorkflow](https://github.com/genXdev/GenXdev.AI/tree/main#createcomfyuniversalworkflow) | &nbsp; | Creates comprehensive ComfyUI workflow configuration supporting all parameters |
| [DownloadComfyResults](https://github.com/genXdev/GenXdev.AI/tree/main#downloadcomfyresults) | &nbsp; | Downloads generated results from ComfyUI server with file information |
| [EnsureComfyUI](https://github.com/genXdev/GenXdev.AI/tree/main#ensurecomfyui) | &nbsp; | Ensures ComfyUI is installed and running with optional window positioning. |
| [EnsureComfyUIModel](https://github.com/genXdev/GenXdev.AI/tree/main#ensurecomfyuimodel) | &nbsp; | Ensures specified ComfyUI models are available locally with automatic download |
| [EnsureDeepStack](https://github.com/genXdev/GenXdev.AI/tree/main#ensuredeepstack) | &nbsp; | Ensures DeepStack face recognition service is installed and running. |
| [EnsureGithubCLIInstalled](https://github.com/genXdev/GenXdev.AI/tree/main#ensuregithubcliinstalled) | &nbsp; | Ensures GitHub CLI is properly installed and configured on the system. |
| [EnsureHuggingFace](https://github.com/genXdev/GenXdev.AI/tree/main#ensurehuggingface) | &nbsp; | Ensures the Hugging Face CLI is installed and functional. |
| [EnsureLMStudio](https://github.com/genXdev/GenXdev.AI/tree/main#ensurelmstudio) | &nbsp; | Ensures LM Studio is properly initialized with the specified model. |
| [EnsurePaintNet](https://github.com/genXdev/GenXdev.AI/tree/main#ensurepaintnet) | &nbsp; | Ensures Paint.NET is properly installed and accessible on the system. |
| [EnsurePip](https://github.com/genXdev/GenXdev.AI/tree/main#ensurepip) | &nbsp; | Ensures pip is installed and functional for the specified Python installation. |
| [EnsurePython](https://github.com/genXdev/GenXdev.AI/tree/main#ensurepython) | &nbsp; | Ensures Python is installed and available in the system PATH. |
| [EnsureWinMergeInstalled](https://github.com/genXdev/GenXdev.AI/tree/main#ensurewinmergeinstalled) | &nbsp; | Ensures WinMerge is installed and available for file comparison operations. |
| [Export-ImageIndex](https://github.com/genXdev/GenXdev.AI/tree/main#export-imageindex) | indeximages | Initializes and populates the SQLite database by discovering images directly. |
| [Find-Image](https://github.com/genXdev/GenXdev.AI/tree/main#find-image) | findimages, li | &nbsp; |
| [Find-IndexedImage](https://github.com/genXdev/GenXdev.AI/tree/main#find-indexedimage) | findindexedimages, lii | Searches for images using an optimized SQLite database with fast indexed lookups. |
| [GenerateMasonryLayoutHtml](https://github.com/genXdev/GenXdev.AI/tree/main#generatemasonrylayouthtml) | &nbsp; | Generates a responsive masonry layout HTML gallery from image data. |
| [Get-AIDefaultLLMSettings](https://github.com/genXdev/GenXdev.AI/tree/main#get-aidefaultllmsettings) | &nbsp; | Gets all available default LLM settings configurations for AI operations in GenXdev.AI. |
| [Get-AIImageCollection](https://github.com/genXdev/GenXdev.AI/tree/main#get-aiimagecollection) | getimgdirs | Gets the configured directories for image files used in GenXdev.AI operations. |
| [Get-AIKnownFacesRootpath](https://github.com/genXdev/GenXdev.AI/tree/main#get-aiknownfacesrootpath) | &nbsp; | &nbsp; |
| [Get-AILLMSettings](https://github.com/genXdev/GenXdev.AI/tree/main#get-aillmsettings) | &nbsp; | Gets the LLM settings for AI operations in GenXdev.AI. |
| [Get-AIMetaLanguage](https://github.com/genXdev/GenXdev.AI/tree/main#get-aimetalanguage) | getimgmetalang | Gets the configured default language for image metadata operations. |
| [Get-ComfyUIModelPath](https://github.com/genXdev/GenXdev.AI/tree/main#get-comfyuimodelpath) | &nbsp; | Gets the correct ComfyUI models directory path for the current installation |
| [Get-CpuCore](https://github.com/genXdev/GenXdev.AI/tree/main#get-cpucore) | &nbsp; | Calculates and returns the total number of logical CPU cores in the system. |
| [Get-Fallacy](https://github.com/genXdev/GenXdev.AI/tree/main#get-fallacy) | dispicetext | Analyzes text to identify logical fallacies using AI-powered detection. |
| [Get-HasCapableGpu](https://github.com/genXdev/GenXdev.AI/tree/main#get-hascapablegpu) | &nbsp; | Determines if a CUDA-capable GPU with sufficient memory is present. |
| [Get-ImageDetectedFaces](https://github.com/genXdev/GenXdev.AI/tree/main#get-imagedetectedfaces) | &nbsp; | &nbsp; |
| [Get-ImageDetectedObjects](https://github.com/genXdev/GenXdev.AI/tree/main#get-imagedetectedobjects) | &nbsp; | Detects and classifies objects in an uploaded image using DeepStack. |
| [Get-ImageDetectedScenes](https://github.com/genXdev/GenXdev.AI/tree/main#get-imagedetectedscenes) | &nbsp; | Classifies an image into one of 365 scene categories using DeepStack. |
| [Get-ImageIndexPath](https://github.com/genXdev/GenXdev.AI/tree/main#get-imageindexpath) | &nbsp; | Returns the path to the image database, initializing or rebuilding it if needed. |
| [Get-ImageIndexStats](https://github.com/genXdev/GenXdev.AI/tree/main#get-imageindexstats) | getimagedbstats, gids | Retrieves comprehensive statistics and information about the image database. |
| [Get-LMStudioLoadedModelList](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudioloadedmodellist) | &nbsp; | Retrieves the list of currently loaded models from LM Studio. |
| [Get-LMStudioModelList](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiomodellist) | &nbsp; | Retrieves a list of installed LM Studio models. |
| [Get-LMStudioPaths](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiopaths) | &nbsp; | Retrieves file paths for LM Studio executables. |
| [Get-LMStudioTextEmbedding](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiotextembedding) | &nbsp; | Gets text embeddings from LM Studio model. |
| [Get-LMStudioWindow](https://github.com/genXdev/GenXdev.AI/tree/main#get-lmstudiowindow) | lmstudiowindow, setlmstudiowindow | Gets a window helper for the LM Studio application. |
| [Get-NumberOfCpuCores](https://github.com/genXdev/GenXdev.AI/tree/main#get-numberofcpucores) | &nbsp; | Calculates and returns the total number of logical CPU cores in the system. |
| [Get-RegisteredFaces](https://github.com/genXdev/GenXdev.AI/tree/main#get-registeredfaces) | &nbsp; | Retrieves a list of all registered face identifiers from DeepStack. |
| [Get-ScriptExecutionErrorFixPrompt](https://github.com/genXdev/GenXdev.AI/tree/main#get-scriptexecutionerrorfixprompt) | getfixprompt | Captures error messages from various streams and uses LLM to suggest fixes. |
| [Get-SimularMovieTitles](https://github.com/genXdev/GenXdev.AI/tree/main#get-simularmovietitles) | &nbsp; | Finds similar movie titles based on common properties. |
| [Get-TextTranslation](https://github.com/genXdev/GenXdev.AI/tree/main#get-texttranslation) | translate | Translates text to another language using AI. |
| [Get-VectorSimilarity](https://github.com/genXdev/GenXdev.AI/tree/main#get-vectorsimilarity) | &nbsp; | &nbsp; |
| [Initialize-LMStudioModel](https://github.com/genXdev/GenXdev.AI/tree/main#initialize-lmstudiomodel) | initlmstudio | Initializes and loads an AI model in LM Studio. |
| [Install-LMStudioApplication](https://github.com/genXdev/GenXdev.AI/tree/main#install-lmstudioapplication) | &nbsp; | Installs LM Studio application using WinGet package manager. |
| [Invoke-AIPowershellCommand](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-aipowershellcommand) | hint | Converts AI command suggestions to JSON format for processing. |
| [Invoke-ComfyUIImageGeneration](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-comfyuiimagegeneration) | generateimage | &nbsp; |
| [Invoke-CommandFromToolCall](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-commandfromtoolcall) | &nbsp; | Executes a tool call function with validation and parameter filtering. |
| [Invoke-HuggingFaceCli](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-huggingfacecli) | &nbsp; | Invokes the Hugging Face CLI with the specified arguments. |
| [Invoke-ImageEnhancement](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imageenhancement) | enhanceimage | Enhances an image by enlarging it 4X while improving quality using DeepStack. |
| [Invoke-ImageFacesUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagefacesupdate) | imagepeopledetection | Updates face recognition metadata for image files in a specified directory. |
| [Invoke-ImageKeywordUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagekeywordupdate) | imagekeywordgeneration | Updates image metadata with AI-generated descriptions and keywords. |
| [Invoke-ImageMetadataUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagemetadataupdate) | imagepropdetection | Updates EXIF metadata for images in a directory. |
| [Invoke-ImageObjectsUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imageobjectsupdate) | imageobjectdetection | Updates object detection metadata for image files in a specified directory. |
| [Invoke-ImageScenesUpdate](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-imagescenesupdate) | imagescenedetection | Updates scene classification metadata for image files in a specified directory. |
| [Invoke-LLMBooleanEvaluation](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmbooleanevaluation) | equalstrue | Evaluates a statement using AI to determine if it's true or false. |
| [Invoke-LLMQuery](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmquery) | llm, qllm | &nbsp; |
| [Invoke-LLMStringListEvaluation](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmstringlistevaluation) | getlist, getstring | &nbsp; |
| [Invoke-LLMTextTransformation](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-llmtexttransformation) | spellcheck | Transforms text using AI-powered processing. |
| [Invoke-QueryImageContent](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-queryimagecontent) | &nbsp; | Analyzes image content using AI vision capabilities through the LM-Studio API. |
| [Invoke-WinMerge](https://github.com/genXdev/GenXdev.AI/tree/main#invoke-winmerge) | &nbsp; | Launches WinMerge to compare two files side by side. |
| [New-LLMAudioChat](https://github.com/genXdev/GenXdev.AI/tree/main#new-llmaudiochat) | llmaudiochat | Creates an interactive audio chat session with an LLM model. |
| [New-LLMTextChat](https://github.com/genXdev/GenXdev.AI/tree/main#new-llmtextchat) | llmchat | Starts an interactive text chat session with AI capabilities. |
| [QueueComfyWorkflow](https://github.com/genXdev/GenXdev.AI/tree/main#queuecomfyworkflow) | &nbsp; | Submits workflow to ComfyUI processing queue for execution. |
| [Register-AllFaces](https://github.com/genXdev/GenXdev.AI/tree/main#register-allfaces) | UpdateFaces | Updates all face recognition profiles from image files in the faces directory. |
| [Register-Face](https://github.com/genXdev/GenXdev.AI/tree/main#register-face) | &nbsp; | Registers a new face with the DeepStack face recognition API. |
| [Remove-ImageDirectories](https://github.com/genXdev/GenXdev.AI/tree/main#remove-imagedirectories) | removeimgdir | Removes directories from the configured image directories for GenXdev.AI operations. |
| [Remove-ImageMetaData](https://github.com/genXdev/GenXdev.AI/tree/main#remove-imagemetadata) | removeimagedata | Removes image metadata files from image directories. |
| [ResizeComfyInputImage](https://github.com/genXdev/GenXdev.AI/tree/main#resizecomfyinputimage) | &nbsp; | Resizes input image while preserving aspect ratio for optimal processing. |
| [Save-FoundImageFaces](https://github.com/genXdev/GenXdev.AI/tree/main#save-foundimagefaces) | saveimagefaces | Saves cropped face images from indexed image search results. |
| [Save-FoundImageObjects](https://github.com/genXdev/GenXdev.AI/tree/main#save-foundimageobjects) | saveimageObjects | Saves cropped object images from indexed image search results to files. |
| [Save-Transcriptions](https://github.com/genXdev/GenXdev.AI/tree/main#save-transcriptions) | &nbsp; | Generates subtitle files for audio and video files using OpenAI Whisper. |
| [Set-AIImageCollection](https://github.com/genXdev/GenXdev.AI/tree/main#set-aiimagecollection) | &nbsp; | &nbsp; |
| [Set-AIKnownFacesRootpath](https://github.com/genXdev/GenXdev.AI/tree/main#set-aiknownfacesrootpath) | &nbsp; | Sets the directory for face image files used in GenXdev.AI operations. |
| [Set-AILLMSettings](https://github.com/genXdev/GenXdev.AI/tree/main#set-aillmsettings) | &nbsp; | Sets the LLM settings for AI operations in GenXdev.AI. |
| [Set-AIMetaLanguage](https://github.com/genXdev/GenXdev.AI/tree/main#set-aimetalanguage) | &nbsp; | &nbsp; |
| [Set-ComfyUIBackgroundImage](https://github.com/genXdev/GenXdev.AI/tree/main#set-comfyuibackgroundimage) | &nbsp; | Sets or clears the background image for ComfyUI's canvas interface |
| [Set-ComfyUIModelPath](https://github.com/genXdev/GenXdev.AI/tree/main#set-comfyuimodelpath) | &nbsp; | Adds a custom model path to ComfyUI's extra_model_paths.yaml configuration |
| [Set-GenXdevAICommandNotFoundAction](https://github.com/genXdev/GenXdev.AI/tree/main#set-genxdevaicommandnotfoundaction) | &nbsp; | Sets up custom command not found handling with AI assistance. |
| [Set-ImageIndexPath](https://github.com/genXdev/GenXdev.AI/tree/main#set-imageindexpath) | &nbsp; | Sets the default database file path for image operations in GenXdev.AI. |
| [Set-WindowsWallpaperEx](https://github.com/genXdev/GenXdev.AI/tree/main#set-windowswallpaperex) | nextwallpaper | Sets a random wallpaper from a specified directory or search criteria. |
| [SetComfyUIProcessPriority](https://github.com/genXdev/GenXdev.AI/tree/main#setcomfyuiprocesspriority) | &nbsp; | Sets ComfyUI processes to IDLE priority for CPU mode processing optimization. |
| [Show-FoundImagesInBrowser](https://github.com/genXdev/GenXdev.AI/tree/main#show-foundimagesinbrowser) | showfoundimages | Displays image search results in a masonry layout web gallery. |
| [Show-GenXdevScriptErrorFixInIde](https://github.com/genXdev/GenXdev.AI/tree/main#show-genxdevscripterrorfixinide) | letsfixthis | Executes a script block and analyzes errors using AI to generate fixes in IDE. |
| [Start-AudioTranscription](https://github.com/genXdev/GenXdev.AI/tree/main#start-audiotranscription) | transcribe, transcribefile | Transcribes an audio file, video file, or a recording device to text |
| [Start-GenXdevMCPServer](https://github.com/genXdev/GenXdev.AI/tree/main#start-genxdevmcpserver) | &nbsp; | Starts the GenXdev MCP server that exposes PowerShell cmdlets as tools. |
| [Start-LMStudioApplication](https://github.com/genXdev/GenXdev.AI/tree/main#start-lmstudioapplication) | &nbsp; | Starts the LM Studio application if it's not already running. |
| [Stop-ComfyUI](https://github.com/genXdev/GenXdev.AI/tree/main#stop-comfyui) | &nbsp; | Terminates all running ComfyUI processes and releases associated resources. |
| [Test-ComfyUIQueueEmpty](https://github.com/genXdev/GenXdev.AI/tree/main#test-comfyuiqueueempty) | &nbsp; | Checks if the ComfyUI processing queue is empty |
| [Test-DeepLinkImageFile](https://github.com/genXdev/GenXdev.AI/tree/main#test-deeplinkimagefile) | &nbsp; | Tests if the specified file path is a valid image file with a supported format. |
| [Test-LMStudioInstallation](https://github.com/genXdev/GenXdev.AI/tree/main#test-lmstudioinstallation) | &nbsp; | Tests if LMStudio is installed and accessible on the system. |
| [Test-LMStudioProcess](https://github.com/genXdev/GenXdev.AI/tree/main#test-lmstudioprocess) | &nbsp; | Tests if LM Studio process is running and configures its window state. |
| [Unregister-AllFaces](https://github.com/genXdev/GenXdev.AI/tree/main#unregister-allfaces) | &nbsp; | Removes all registered faces from the DeepStack face recognition system. |
| [Unregister-Face](https://github.com/genXdev/GenXdev.AI/tree/main#unregister-face) | &nbsp; | Deletes a registered face by its identifier from DeepStack. |
| [Update-AllImageMetaData](https://github.com/genXdev/GenXdev.AI/tree/main#update-allimagemetadata) | updateallimages | &nbsp; |
| [UploadComfyImage](https://github.com/genXdev/GenXdev.AI/tree/main#uploadcomfyimage) | &nbsp; | Uploads image file to ComfyUI server for processing workflow integration. |
| [WaitForComfyCompletion](https://github.com/genXdev/GenXdev.AI/tree/main#waitforcomfycompletion) | &nbsp; | Waits for ComfyUI workflow completion with progress monitoring |

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
| [Add-LineToREADME](https://github.com/genXdev/GenXdev.Coding/tree/main#add-linetoreadme) | &nbsp; | Adds a line to a README.md markdown file in a specified section. |
| [Add-MissingGenXdevUnitTests](https://github.com/genXdev/GenXdev.Coding/tree/main#add-missinggenxdevunittests) | &nbsp; | &nbsp; |
| [Add-ReleaseNoteLineToREADME](https://github.com/genXdev/GenXdev.Coding/tree/main#add-releasenotelinetoreadme) | releasenote | Adds a ReleaseNote line to the README file with a timestamp. |
| [Add-TodoLineToREADME](https://github.com/genXdev/GenXdev.Coding/tree/main#add-todolinetoreadme) | todo | Adds a todo item to the README.md file. |
| [Assert-GenXdevCmdlet](https://github.com/genXdev/GenXdev.Coding/tree/main#assert-genxdevcmdlet) | improvecmdlet | Improves GenXdev cmdlet documentation and implementation through AI assistance. |
| [Assert-GenXdevCmdletTests](https://github.com/genXdev/GenXdev.Coding/tree/main#assert-genxdevcmdlettests) | improvecmdlettests | Asserts and improves unit-tests of a specified GenXdev cmdlet. |
| [Assert-GenXdevDependencyUsage](https://github.com/genXdev/GenXdev.Coding/tree/main#assert-genxdevdependencyusage) | checkgenxdevdependencies | &nbsp; |
| [Assert-GenXdevTest](https://github.com/genXdev/GenXdev.Coding/tree/main#assert-genxdevtest) | rungenxdevtests | &nbsp; |
| [Assert-ModuleDefinition](https://github.com/genXdev/GenXdev.Coding/tree/main#assert-moduledefinition) | &nbsp; | Assists in refactoring PowerShell source code files using AI assistance. |
| [Assert-RefactorFile](https://github.com/genXdev/GenXdev.Coding/tree/main#assert-refactorfile) | &nbsp; | &nbsp; |
| [Clear-GenXdevModules](https://github.com/genXdev/GenXdev.Coding/tree/main#clear-genxdevmodules) | cleangenxdev | Cleans build artifacts from GenXdev PowerShell modules. |
| [Complete-GenXDevREADME](https://github.com/genXdev/GenXdev.Coding/tree/main#complete-genxdevreadme) | &nbsp; | Completes the README file for specified GenXDev modules by adding documentation. |
| [EnsureCopilotKeyboardShortCut](https://github.com/genXdev/GenXdev.Coding/tree/main#ensurecopilotkeyboardshortcut) | &nbsp; | Configures the GitHub Copilot Chat keyboard shortcuts in Visual Studio Code. |
| [EnsureDefaultGenXdevRefactors](https://github.com/genXdev/GenXdev.Coding/tree/main#ensuredefaultgenxdevrefactors) | &nbsp; | &nbsp; |
| [EnsureVSCodeInstallation](https://github.com/genXdev/GenXdev.Coding/tree/main#ensurevscodeinstallation) | &nbsp; | Installs and configures Visual Studio Code with recommended extensions. |
| [Features](https://github.com/genXdev/GenXdev.Coding/tree/main#features) | &nbsp; | Displays features from a README.md file. |
| [Get-GenXdevCmdletUsageAnalysis](https://github.com/genXdev/GenXdev.Coding/tree/main#get-genxdevcmdletusageanalysis) | &nbsp; | Analyzes GenXdev cmdlet usage patterns to identify most frequently called functions. |
| [Get-GenXDevModule](https://github.com/genXdev/GenXdev.Coding/tree/main#get-genxdevmodule) | &nbsp; | Retrieves all GenXDev modules from a specified path. |
| [Get-GenXDevModuleInfo](https://github.com/genXdev/GenXdev.Coding/tree/main#get-genxdevmoduleinfo) | &nbsp; | Retrieves detailed information about GenXdev PowerShell modules. |
| [Get-GenXDevNewModulesInOrderOfDependency](https://github.com/genXdev/GenXdev.Coding/tree/main#get-genxdevnewmodulesinorderofdependency) | &nbsp; | Retrieves GenXDev modules in dependency order. |
| [Get-GitChangedFiles](https://github.com/genXdev/GenXdev.Coding/tree/main#get-gitchangedfiles) | gitchanged | Get the list of changed files in a Git repository. |
| [Get-ModuleHelpMarkdown](https://github.com/genXdev/GenXdev.Coding/tree/main#get-modulehelpmarkdown) | &nbsp; | Generates markdown help documentation for specified GenXDev modules. |
| [Get-Refactor](https://github.com/genXdev/GenXdev.Coding/tree/main#get-refactor) | refactors | Retrieves refactor definitions from GenXdev preferences based on name patterns. |
| [Get-RefactorReport](https://github.com/genXdev/GenXdev.Coding/tree/main#get-refactorreport) | refactorreport | Generates a detailed report of refactoring operations and their status. |
| [Ideas](https://github.com/genXdev/GenXdev.Coding/tree/main#ideas) | &nbsp; | Displays ideas from a README.md file. |
| [Invoke-GenXdevPSFormatter](https://github.com/genXdev/GenXdev.Coding/tree/main#invoke-genxdevpsformatter) | &nbsp; | Formats PowerShell script files using PSScriptAnalyzer formatting rules. |
| [Invoke-GenXdevScriptAnalyzer](https://github.com/genXdev/GenXdev.Coding/tree/main#invoke-genxdevscriptanalyzer) | &nbsp; | &nbsp; |
| [Issues](https://github.com/genXdev/GenXdev.Coding/tree/main#issues) | &nbsp; | Displays issues from a README.md file. |
| [New-GenXdevCmdlet](https://github.com/genXdev/GenXdev.Coding/tree/main#new-genxdevcmdlet) | newcmd | Creates a new GenXdev PowerShell cmdlet with proper structure and validation. |
| [New-GenXdevModule](https://github.com/genXdev/GenXdev.Coding/tree/main#new-genxdevmodule) | &nbsp; | Creates a new GenXdev PowerShell module with proper structure and configuration. |
| [New-GitCommit](https://github.com/genXdev/GenXdev.Coding/tree/main#new-gitcommit) | commit | Creates and pushes a new git commit with all changes. |
| [New-PullRequestForGenXdevModuleChanges](https://github.com/genXdev/GenXdev.Coding/tree/main#new-pullrequestforgenxdevmodulechanges) | prgenxdevmodule | Creates a pull request for changes made to a GenXdev module. |
| [New-Refactor](https://github.com/genXdev/GenXdev.Coding/tree/main#new-refactor) | newrefactor | Creates a new refactoring set for code transformation tasks. |
| [Open-GenXdevCmdletsContainingClipboardTextInIde](https://github.com/genXdev/GenXdev.Coding/tree/main#open-genxdevcmdletscontainingclipboardtextinide) | vscodesearch | Opens files in IDE that contain clipboard text |
| [Open-SourceFileInIde](https://github.com/genXdev/GenXdev.Coding/tree/main#open-sourcefileinide) | editcode | Opens a source file in the preferred IDE (Visual Studio Code or Visual Studio). |
| [PermanentlyDeleteGitFolders](https://github.com/genXdev/GenXdev.Coding/tree/main#permanentlydeletegitfolders) | &nbsp; | Permanently deletes specified folders from all branches in a Git repository. |
| [ReleaseNotes](https://github.com/genXdev/GenXdev.Coding/tree/main#releasenotes) | &nbsp; | Displays ReleaseNotes from a README.md file. |
| [Remove-Refactor](https://github.com/genXdev/GenXdev.Coding/tree/main#remove-refactor) | &nbsp; | Removes refactor sets from GenXdev preferences system. |
| [Search-GenXdevCmdlet](https://github.com/genXdev/GenXdev.Coding/tree/main#search-genxdevcmdlet) | searchcmdlet | Searches for a GenXdev cmdlet and optionally opens it in an IDE for editing. |
| [Show-GenXdevCmdLetInIde](https://github.com/genXdev/GenXdev.Coding/tree/main#show-genxdevcmdletinide) | cmdlet, editcmdlet | Opens the specified GenXdev cmdlet in Visual Studio Code. |
| [SplitUpPsm1File](https://github.com/genXdev/GenXdev.Coding/tree/main#splituppsm1file) | &nbsp; | Splits a PowerShell module (.psm1) file into individual function files. |
| [Start-NextRefactor](https://github.com/genXdev/GenXdev.Coding/tree/main#start-nextrefactor) | nextrefactor | Continues or restarts a code refactoring session. |
| [Test-RefactorLLMSelection](https://github.com/genXdev/GenXdev.Coding/tree/main#test-refactorllmselection) | &nbsp; | Evaluates source files for refactoring eligibility using LLM analysis. |
| [Todoos](https://github.com/genXdev/GenXdev.Coding/tree/main#todoos) | &nbsp; | Displays todo items from a README.md file. |
| [Update-Refactor](https://github.com/genXdev/GenXdev.Coding/tree/main#update-refactor) | updaterefactor | Updates and manages refactoring sets including file selection and processing. |
| [VSCode](https://github.com/genXdev/GenXdev.Coding/tree/main#vscode) | &nbsp; | Opens one or more files in Visual Studio Code. |

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
| [Add-LineToREADME](https://github.com/genXdev/GenXdev.Coding/tree/main#add-linetoreadme) | &nbsp; | Adds a line to a README.md markdown file in a specified section. |
| [Add-MissingGenXdevUnitTests](https://github.com/genXdev/GenXdev.Coding/tree/main#add-missinggenxdevunittests) | &nbsp; | &nbsp; |
| [Add-ReleaseNoteLineToREADME](https://github.com/genXdev/GenXdev.Coding/tree/main#add-releasenotelinetoreadme) | releasenote | Adds a ReleaseNote line to the README file with a timestamp. |
| [Add-TodoLineToREADME](https://github.com/genXdev/GenXdev.Coding/tree/main#add-todolinetoreadme) | todo | Adds a todo item to the README.md file. |
| [Assert-GenXdevCmdlet](https://github.com/genXdev/GenXdev.Coding/tree/main#assert-genxdevcmdlet) | improvecmdlet | Improves GenXdev cmdlet documentation and implementation through AI assistance. |
| [Assert-GenXdevCmdletTests](https://github.com/genXdev/GenXdev.Coding/tree/main#assert-genxdevcmdlettests) | improvecmdlettests | Asserts and improves unit-tests of a specified GenXdev cmdlet. |
| [Assert-GenXdevDependencyUsage](https://github.com/genXdev/GenXdev.Coding/tree/main#assert-genxdevdependencyusage) | checkgenxdevdependencies | &nbsp; |
| [Assert-GenXdevTest](https://github.com/genXdev/GenXdev.Coding/tree/main#assert-genxdevtest) | rungenxdevtests | &nbsp; |
| [Assert-ModuleDefinition](https://github.com/genXdev/GenXdev.Coding/tree/main#assert-moduledefinition) | &nbsp; | Assists in refactoring PowerShell source code files using AI assistance. |
| [Assert-RefactorFile](https://github.com/genXdev/GenXdev.Coding/tree/main#assert-refactorfile) | &nbsp; | &nbsp; |
| [Clear-GenXdevModules](https://github.com/genXdev/GenXdev.Coding/tree/main#clear-genxdevmodules) | cleangenxdev | Cleans build artifacts from GenXdev PowerShell modules. |
| [Complete-GenXDevREADME](https://github.com/genXdev/GenXdev.Coding/tree/main#complete-genxdevreadme) | &nbsp; | Completes the README file for specified GenXDev modules by adding documentation. |
| [EnsureCopilotKeyboardShortCut](https://github.com/genXdev/GenXdev.Coding/tree/main#ensurecopilotkeyboardshortcut) | &nbsp; | Configures the GitHub Copilot Chat keyboard shortcuts in Visual Studio Code. |
| [EnsureDefaultGenXdevRefactors](https://github.com/genXdev/GenXdev.Coding/tree/main#ensuredefaultgenxdevrefactors) | &nbsp; | &nbsp; |
| [EnsureVSCodeInstallation](https://github.com/genXdev/GenXdev.Coding/tree/main#ensurevscodeinstallation) | &nbsp; | Installs and configures Visual Studio Code with recommended extensions. |
| [Features](https://github.com/genXdev/GenXdev.Coding/tree/main#features) | &nbsp; | Displays features from a README.md file. |
| [Get-GenXdevCmdletUsageAnalysis](https://github.com/genXdev/GenXdev.Coding/tree/main#get-genxdevcmdletusageanalysis) | &nbsp; | Analyzes GenXdev cmdlet usage patterns to identify most frequently called functions. |
| [Get-GenXDevModule](https://github.com/genXdev/GenXdev.Coding/tree/main#get-genxdevmodule) | &nbsp; | Retrieves all GenXDev modules from a specified path. |
| [Get-GenXDevModuleInfo](https://github.com/genXdev/GenXdev.Coding/tree/main#get-genxdevmoduleinfo) | &nbsp; | Retrieves detailed information about GenXdev PowerShell modules. |
| [Get-GenXDevNewModulesInOrderOfDependency](https://github.com/genXdev/GenXdev.Coding/tree/main#get-genxdevnewmodulesinorderofdependency) | &nbsp; | Retrieves GenXDev modules in dependency order. |
| [Get-GitChangedFiles](https://github.com/genXdev/GenXdev.Coding/tree/main#get-gitchangedfiles) | gitchanged | Get the list of changed files in a Git repository. |
| [Get-ModuleHelpMarkdown](https://github.com/genXdev/GenXdev.Coding/tree/main#get-modulehelpmarkdown) | &nbsp; | Generates markdown help documentation for specified GenXDev modules. |
| [Get-Refactor](https://github.com/genXdev/GenXdev.Coding/tree/main#get-refactor) | refactors | Retrieves refactor definitions from GenXdev preferences based on name patterns. |
| [Get-RefactorReport](https://github.com/genXdev/GenXdev.Coding/tree/main#get-refactorreport) | refactorreport | Generates a detailed report of refactoring operations and their status. |
| [Ideas](https://github.com/genXdev/GenXdev.Coding/tree/main#ideas) | &nbsp; | Displays ideas from a README.md file. |
| [Invoke-GenXdevPSFormatter](https://github.com/genXdev/GenXdev.Coding/tree/main#invoke-genxdevpsformatter) | &nbsp; | Formats PowerShell script files using PSScriptAnalyzer formatting rules. |
| [Invoke-GenXdevScriptAnalyzer](https://github.com/genXdev/GenXdev.Coding/tree/main#invoke-genxdevscriptanalyzer) | &nbsp; | &nbsp; |
| [Issues](https://github.com/genXdev/GenXdev.Coding/tree/main#issues) | &nbsp; | Displays issues from a README.md file. |
| [New-GenXdevCmdlet](https://github.com/genXdev/GenXdev.Coding/tree/main#new-genxdevcmdlet) | newcmd | Creates a new GenXdev PowerShell cmdlet with proper structure and validation. |
| [New-GenXdevModule](https://github.com/genXdev/GenXdev.Coding/tree/main#new-genxdevmodule) | &nbsp; | Creates a new GenXdev PowerShell module with proper structure and configuration. |
| [New-GitCommit](https://github.com/genXdev/GenXdev.Coding/tree/main#new-gitcommit) | commit | Creates and pushes a new git commit with all changes. |
| [New-PullRequestForGenXdevModuleChanges](https://github.com/genXdev/GenXdev.Coding/tree/main#new-pullrequestforgenxdevmodulechanges) | prgenxdevmodule | Creates a pull request for changes made to a GenXdev module. |
| [New-Refactor](https://github.com/genXdev/GenXdev.Coding/tree/main#new-refactor) | newrefactor | Creates a new refactoring set for code transformation tasks. |
| [Open-GenXdevCmdletsContainingClipboardTextInIde](https://github.com/genXdev/GenXdev.Coding/tree/main#open-genxdevcmdletscontainingclipboardtextinide) | vscodesearch | Opens files in IDE that contain clipboard text |
| [Open-SourceFileInIde](https://github.com/genXdev/GenXdev.Coding/tree/main#open-sourcefileinide) | editcode | Opens a source file in the preferred IDE (Visual Studio Code or Visual Studio). |
| [PermanentlyDeleteGitFolders](https://github.com/genXdev/GenXdev.Coding/tree/main#permanentlydeletegitfolders) | &nbsp; | Permanently deletes specified folders from all branches in a Git repository. |
| [ReleaseNotes](https://github.com/genXdev/GenXdev.Coding/tree/main#releasenotes) | &nbsp; | Displays ReleaseNotes from a README.md file. |
| [Remove-Refactor](https://github.com/genXdev/GenXdev.Coding/tree/main#remove-refactor) | &nbsp; | Removes refactor sets from GenXdev preferences system. |
| [Search-GenXdevCmdlet](https://github.com/genXdev/GenXdev.Coding/tree/main#search-genxdevcmdlet) | searchcmdlet | Searches for a GenXdev cmdlet and optionally opens it in an IDE for editing. |
| [Show-GenXdevCmdLetInIde](https://github.com/genXdev/GenXdev.Coding/tree/main#show-genxdevcmdletinide) | cmdlet, editcmdlet | Opens the specified GenXdev cmdlet in Visual Studio Code. |
| [SplitUpPsm1File](https://github.com/genXdev/GenXdev.Coding/tree/main#splituppsm1file) | &nbsp; | Splits a PowerShell module (.psm1) file into individual function files. |
| [Start-NextRefactor](https://github.com/genXdev/GenXdev.Coding/tree/main#start-nextrefactor) | nextrefactor | Continues or restarts a code refactoring session. |
| [Test-RefactorLLMSelection](https://github.com/genXdev/GenXdev.Coding/tree/main#test-refactorllmselection) | &nbsp; | Evaluates source files for refactoring eligibility using LLM analysis. |
| [Todoos](https://github.com/genXdev/GenXdev.Coding/tree/main#todoos) | &nbsp; | Displays todo items from a README.md file. |
| [Update-Refactor](https://github.com/genXdev/GenXdev.Coding/tree/main#update-refactor) | updaterefactor | Updates and manages refactoring sets including file selection and processing. |
| [VSCode](https://github.com/genXdev/GenXdev.Coding/tree/main#vscode) | &nbsp; | Opens one or more files in Visual Studio Code. |

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
| [Add-LineToREADME](https://github.com/genXdev/GenXdev.Coding/tree/main#add-linetoreadme) | &nbsp; | Adds a line to a README.md markdown file in a specified section. |
| [Add-MissingGenXdevUnitTests](https://github.com/genXdev/GenXdev.Coding/tree/main#add-missinggenxdevunittests) | &nbsp; | &nbsp; |
| [Add-ReleaseNoteLineToREADME](https://github.com/genXdev/GenXdev.Coding/tree/main#add-releasenotelinetoreadme) | releasenote | Adds a ReleaseNote line to the README file with a timestamp. |
| [Add-TodoLineToREADME](https://github.com/genXdev/GenXdev.Coding/tree/main#add-todolinetoreadme) | todo | Adds a todo item to the README.md file. |
| [Assert-GenXdevCmdlet](https://github.com/genXdev/GenXdev.Coding/tree/main#assert-genxdevcmdlet) | improvecmdlet | Improves GenXdev cmdlet documentation and implementation through AI assistance. |
| [Assert-GenXdevCmdletTests](https://github.com/genXdev/GenXdev.Coding/tree/main#assert-genxdevcmdlettests) | improvecmdlettests | Asserts and improves unit-tests of a specified GenXdev cmdlet. |
| [Assert-GenXdevDependencyUsage](https://github.com/genXdev/GenXdev.Coding/tree/main#assert-genxdevdependencyusage) | checkgenxdevdependencies | &nbsp; |
| [Assert-GenXdevTest](https://github.com/genXdev/GenXdev.Coding/tree/main#assert-genxdevtest) | rungenxdevtests | &nbsp; |
| [Assert-ModuleDefinition](https://github.com/genXdev/GenXdev.Coding/tree/main#assert-moduledefinition) | &nbsp; | Assists in refactoring PowerShell source code files using AI assistance. |
| [Assert-RefactorFile](https://github.com/genXdev/GenXdev.Coding/tree/main#assert-refactorfile) | &nbsp; | &nbsp; |
| [Clear-GenXdevModules](https://github.com/genXdev/GenXdev.Coding/tree/main#clear-genxdevmodules) | cleangenxdev | Cleans build artifacts from GenXdev PowerShell modules. |
| [Complete-GenXDevREADME](https://github.com/genXdev/GenXdev.Coding/tree/main#complete-genxdevreadme) | &nbsp; | Completes the README file for specified GenXDev modules by adding documentation. |
| [EnsureCopilotKeyboardShortCut](https://github.com/genXdev/GenXdev.Coding/tree/main#ensurecopilotkeyboardshortcut) | &nbsp; | Configures the GitHub Copilot Chat keyboard shortcuts in Visual Studio Code. |
| [EnsureDefaultGenXdevRefactors](https://github.com/genXdev/GenXdev.Coding/tree/main#ensuredefaultgenxdevrefactors) | &nbsp; | &nbsp; |
| [EnsureVSCodeInstallation](https://github.com/genXdev/GenXdev.Coding/tree/main#ensurevscodeinstallation) | &nbsp; | Installs and configures Visual Studio Code with recommended extensions. |
| [Features](https://github.com/genXdev/GenXdev.Coding/tree/main#features) | &nbsp; | Displays features from a README.md file. |
| [Get-GenXdevCmdletUsageAnalysis](https://github.com/genXdev/GenXdev.Coding/tree/main#get-genxdevcmdletusageanalysis) | &nbsp; | Analyzes GenXdev cmdlet usage patterns to identify most frequently called functions. |
| [Get-GenXDevModule](https://github.com/genXdev/GenXdev.Coding/tree/main#get-genxdevmodule) | &nbsp; | Retrieves all GenXDev modules from a specified path. |
| [Get-GenXDevModuleInfo](https://github.com/genXdev/GenXdev.Coding/tree/main#get-genxdevmoduleinfo) | &nbsp; | Retrieves detailed information about GenXdev PowerShell modules. |
| [Get-GenXDevNewModulesInOrderOfDependency](https://github.com/genXdev/GenXdev.Coding/tree/main#get-genxdevnewmodulesinorderofdependency) | &nbsp; | Retrieves GenXDev modules in dependency order. |
| [Get-GitChangedFiles](https://github.com/genXdev/GenXdev.Coding/tree/main#get-gitchangedfiles) | gitchanged | Get the list of changed files in a Git repository. |
| [Get-ModuleHelpMarkdown](https://github.com/genXdev/GenXdev.Coding/tree/main#get-modulehelpmarkdown) | &nbsp; | Generates markdown help documentation for specified GenXDev modules. |
| [Get-Refactor](https://github.com/genXdev/GenXdev.Coding/tree/main#get-refactor) | refactors | Retrieves refactor definitions from GenXdev preferences based on name patterns. |
| [Get-RefactorReport](https://github.com/genXdev/GenXdev.Coding/tree/main#get-refactorreport) | refactorreport | Generates a detailed report of refactoring operations and their status. |
| [Ideas](https://github.com/genXdev/GenXdev.Coding/tree/main#ideas) | &nbsp; | Displays ideas from a README.md file. |
| [Invoke-GenXdevPSFormatter](https://github.com/genXdev/GenXdev.Coding/tree/main#invoke-genxdevpsformatter) | &nbsp; | Formats PowerShell script files using PSScriptAnalyzer formatting rules. |
| [Invoke-GenXdevScriptAnalyzer](https://github.com/genXdev/GenXdev.Coding/tree/main#invoke-genxdevscriptanalyzer) | &nbsp; | &nbsp; |
| [Issues](https://github.com/genXdev/GenXdev.Coding/tree/main#issues) | &nbsp; | Displays issues from a README.md file. |
| [New-GenXdevCmdlet](https://github.com/genXdev/GenXdev.Coding/tree/main#new-genxdevcmdlet) | newcmd | Creates a new GenXdev PowerShell cmdlet with proper structure and validation. |
| [New-GenXdevModule](https://github.com/genXdev/GenXdev.Coding/tree/main#new-genxdevmodule) | &nbsp; | Creates a new GenXdev PowerShell module with proper structure and configuration. |
| [New-GitCommit](https://github.com/genXdev/GenXdev.Coding/tree/main#new-gitcommit) | commit | Creates and pushes a new git commit with all changes. |
| [New-PullRequestForGenXdevModuleChanges](https://github.com/genXdev/GenXdev.Coding/tree/main#new-pullrequestforgenxdevmodulechanges) | prgenxdevmodule | Creates a pull request for changes made to a GenXdev module. |
| [New-Refactor](https://github.com/genXdev/GenXdev.Coding/tree/main#new-refactor) | newrefactor | Creates a new refactoring set for code transformation tasks. |
| [Open-GenXdevCmdletsContainingClipboardTextInIde](https://github.com/genXdev/GenXdev.Coding/tree/main#open-genxdevcmdletscontainingclipboardtextinide) | vscodesearch | Opens files in IDE that contain clipboard text |
| [Open-SourceFileInIde](https://github.com/genXdev/GenXdev.Coding/tree/main#open-sourcefileinide) | editcode | Opens a source file in the preferred IDE (Visual Studio Code or Visual Studio). |
| [PermanentlyDeleteGitFolders](https://github.com/genXdev/GenXdev.Coding/tree/main#permanentlydeletegitfolders) | &nbsp; | Permanently deletes specified folders from all branches in a Git repository. |
| [ReleaseNotes](https://github.com/genXdev/GenXdev.Coding/tree/main#releasenotes) | &nbsp; | Displays ReleaseNotes from a README.md file. |
| [Remove-Refactor](https://github.com/genXdev/GenXdev.Coding/tree/main#remove-refactor) | &nbsp; | Removes refactor sets from GenXdev preferences system. |
| [Search-GenXdevCmdlet](https://github.com/genXdev/GenXdev.Coding/tree/main#search-genxdevcmdlet) | searchcmdlet | Searches for a GenXdev cmdlet and optionally opens it in an IDE for editing. |
| [Show-GenXdevCmdLetInIde](https://github.com/genXdev/GenXdev.Coding/tree/main#show-genxdevcmdletinide) | cmdlet, editcmdlet | Opens the specified GenXdev cmdlet in Visual Studio Code. |
| [SplitUpPsm1File](https://github.com/genXdev/GenXdev.Coding/tree/main#splituppsm1file) | &nbsp; | Splits a PowerShell module (.psm1) file into individual function files. |
| [Start-NextRefactor](https://github.com/genXdev/GenXdev.Coding/tree/main#start-nextrefactor) | nextrefactor | Continues or restarts a code refactoring session. |
| [Test-RefactorLLMSelection](https://github.com/genXdev/GenXdev.Coding/tree/main#test-refactorllmselection) | &nbsp; | Evaluates source files for refactoring eligibility using LLM analysis. |
| [Todoos](https://github.com/genXdev/GenXdev.Coding/tree/main#todoos) | &nbsp; | Displays todo items from a README.md file. |
| [Update-Refactor](https://github.com/genXdev/GenXdev.Coding/tree/main#update-refactor) | updaterefactor | Updates and manages refactoring sets including file selection and processing. |
| [VSCode](https://github.com/genXdev/GenXdev.Coding/tree/main#vscode) | &nbsp; | Opens one or more files in Visual Studio Code. |

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
| [Enable-Screensaver](https://github.com/genXdev/GenXdev.Console/tree/main#enable-screensaver) | &nbsp; | Starts the configured Windows screensaver. |
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
| [New-MicrosoftShellTab](https://github.com/genXdev/GenXdev.Console/tree/main#new-microsoftshelltab) | x | Creates a new Windows Terminal tab running PowerShell. |
| [Now](https://github.com/genXdev/GenXdev.Console/tree/main#now) | &nbsp; | Returns the current system date and time as a DateTime object. |
| [Open-MediaFile](https://github.com/genXdev/GenXdev.Console/tree/main#open-mediafile) | findmedia, media, vlcmedia | &nbsp; |
| [Open-VlcMediaPlayer](https://github.com/genXdev/GenXdev.Console/tree/main#open-vlcmediaplayer) | vlc | Launches and controls VLC Media Player with extensive configuration options. |
| [Open-VlcMediaPlayerLyrics](https://github.com/genXdev/GenXdev.Console/tree/main#open-vlcmediaplayerlyrics) | vlclyrics | Opens a web browser to search for lyrics of currently playing VLC media. |
| [Remove-SpotifyTracksFromLiked](https://github.com/genXdev/GenXdev.Console/tree/main#remove-spotifytracksfromliked) | dislike | Removes tracks from the user's Spotify Library (Liked Songs). |
| [Remove-SpotifyTracksFromPlaylist](https://github.com/genXdev/GenXdev.Console/tree/main#remove-spotifytracksfromplaylist) | removefromplaylist | Removes tracks from a Spotify playlist. |
| [SayDate](https://github.com/genXdev/GenXdev.Console/tree/main#saydate) | &nbsp; | Speaks the current date using text-to-speech synthesis. |
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
| [Set-SpotifyPlaylistOrder](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyplaylistorder) | &nbsp; | &nbsp; |
| [Set-SpotifyPrevious](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyprevious) | prev, previous | Skips to the previous track in Spotify playback. |
| [Set-SpotifyRepeatContext](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyrepeatcontext) | repeat | Enables playlist repeat mode for Spotify playback. |
| [Set-SpotifyRepeatOff](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyrepeatoff) | norepeat, repeatoff | Disables Spotify repeat mode for the currently active device. |
| [Set-SpotifyRepeatSong](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyrepeatsong) | repeatsong | Enables song repeat mode in Spotify. |
| [Set-SpotifyShuffleOff](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyshuffleoff) | noshuffle, shuffleoff | Disables Spotify song-shuffle mode on the active device. |
| [Set-SpotifyShuffleOn](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyshuffleon) | shuffle, shuffleon | Enables Spotify song-shuffle mode. |
| [Set-SpotifyStart](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifystart) | play, startmusic | Starts Spotify playback on the currently active device. |
| [Set-SpotifyStop](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifystop) | stop | Stops Spotify playback on the active device. |
| [Set-VLCPlayerFocused](https://github.com/genXdev/GenXdev.Console/tree/main#set-vlcplayerfocused) | fvlc, showvlc, vlcf | Sets focus to the VLC media player window. |
| [Start-TextToSpeech](https://github.com/genXdev/GenXdev.Console/tree/main#start-texttospeech) | say | Converts text to speech using the Windows Speech API. |
| [Start-VlcMediaPlayerNextInPlaylist](https://github.com/genXdev/GenXdev.Console/tree/main#start-vlcmediaplayernextinplaylist) | vlcnext | Advances VLC Media Player to the next item in the current playlist. |
| [Start-VlcMediaPlayerPreviousInPlaylist](https://github.com/genXdev/GenXdev.Console/tree/main#start-vlcmediaplayerpreviousinplaylist) | vlcback, vlcprev | Moves to the previous item in the VLC Media Player playlist. |
| [Stop-TextToSpeech](https://github.com/genXdev/GenXdev.Console/tree/main#stop-texttospeech) | sst | Immediately stops any ongoing text-to-speech output. |
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
| [Enable-Screensaver](https://github.com/genXdev/GenXdev.Console/tree/main#enable-screensaver) | &nbsp; | Starts the configured Windows screensaver. |
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
| [New-MicrosoftShellTab](https://github.com/genXdev/GenXdev.Console/tree/main#new-microsoftshelltab) | x | Creates a new Windows Terminal tab running PowerShell. |
| [Now](https://github.com/genXdev/GenXdev.Console/tree/main#now) | &nbsp; | Returns the current system date and time as a DateTime object. |
| [Open-MediaFile](https://github.com/genXdev/GenXdev.Console/tree/main#open-mediafile) | findmedia, media, vlcmedia | &nbsp; |
| [Open-VlcMediaPlayer](https://github.com/genXdev/GenXdev.Console/tree/main#open-vlcmediaplayer) | vlc | Launches and controls VLC Media Player with extensive configuration options. |
| [Open-VlcMediaPlayerLyrics](https://github.com/genXdev/GenXdev.Console/tree/main#open-vlcmediaplayerlyrics) | vlclyrics | Opens a web browser to search for lyrics of currently playing VLC media. |
| [Remove-SpotifyTracksFromLiked](https://github.com/genXdev/GenXdev.Console/tree/main#remove-spotifytracksfromliked) | dislike | Removes tracks from the user's Spotify Library (Liked Songs). |
| [Remove-SpotifyTracksFromPlaylist](https://github.com/genXdev/GenXdev.Console/tree/main#remove-spotifytracksfromplaylist) | removefromplaylist | Removes tracks from a Spotify playlist. |
| [SayDate](https://github.com/genXdev/GenXdev.Console/tree/main#saydate) | &nbsp; | Speaks the current date using text-to-speech synthesis. |
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
| [Set-SpotifyPlaylistOrder](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyplaylistorder) | &nbsp; | &nbsp; |
| [Set-SpotifyPrevious](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyprevious) | prev, previous | Skips to the previous track in Spotify playback. |
| [Set-SpotifyRepeatContext](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyrepeatcontext) | repeat | Enables playlist repeat mode for Spotify playback. |
| [Set-SpotifyRepeatOff](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyrepeatoff) | norepeat, repeatoff | Disables Spotify repeat mode for the currently active device. |
| [Set-SpotifyRepeatSong](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyrepeatsong) | repeatsong | Enables song repeat mode in Spotify. |
| [Set-SpotifyShuffleOff](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyshuffleoff) | noshuffle, shuffleoff | Disables Spotify song-shuffle mode on the active device. |
| [Set-SpotifyShuffleOn](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyshuffleon) | shuffle, shuffleon | Enables Spotify song-shuffle mode. |
| [Set-SpotifyStart](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifystart) | play, startmusic | Starts Spotify playback on the currently active device. |
| [Set-SpotifyStop](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifystop) | stop | Stops Spotify playback on the active device. |
| [Set-VLCPlayerFocused](https://github.com/genXdev/GenXdev.Console/tree/main#set-vlcplayerfocused) | fvlc, showvlc, vlcf | Sets focus to the VLC media player window. |
| [Start-TextToSpeech](https://github.com/genXdev/GenXdev.Console/tree/main#start-texttospeech) | say | Converts text to speech using the Windows Speech API. |
| [Start-VlcMediaPlayerNextInPlaylist](https://github.com/genXdev/GenXdev.Console/tree/main#start-vlcmediaplayernextinplaylist) | vlcnext | Advances VLC Media Player to the next item in the current playlist. |
| [Start-VlcMediaPlayerPreviousInPlaylist](https://github.com/genXdev/GenXdev.Console/tree/main#start-vlcmediaplayerpreviousinplaylist) | vlcback, vlcprev | Moves to the previous item in the VLC Media Player playlist. |
| [Stop-TextToSpeech](https://github.com/genXdev/GenXdev.Console/tree/main#stop-texttospeech) | sst | Immediately stops any ongoing text-to-speech output. |
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
| [Enable-Screensaver](https://github.com/genXdev/GenXdev.Console/tree/main#enable-screensaver) | &nbsp; | Starts the configured Windows screensaver. |
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
| [New-MicrosoftShellTab](https://github.com/genXdev/GenXdev.Console/tree/main#new-microsoftshelltab) | x | Creates a new Windows Terminal tab running PowerShell. |
| [Now](https://github.com/genXdev/GenXdev.Console/tree/main#now) | &nbsp; | Returns the current system date and time as a DateTime object. |
| [Open-MediaFile](https://github.com/genXdev/GenXdev.Console/tree/main#open-mediafile) | findmedia, media, vlcmedia | &nbsp; |
| [Open-VlcMediaPlayer](https://github.com/genXdev/GenXdev.Console/tree/main#open-vlcmediaplayer) | vlc | Launches and controls VLC Media Player with extensive configuration options. |
| [Open-VlcMediaPlayerLyrics](https://github.com/genXdev/GenXdev.Console/tree/main#open-vlcmediaplayerlyrics) | vlclyrics | Opens a web browser to search for lyrics of currently playing VLC media. |
| [Remove-SpotifyTracksFromLiked](https://github.com/genXdev/GenXdev.Console/tree/main#remove-spotifytracksfromliked) | dislike | Removes tracks from the user's Spotify Library (Liked Songs). |
| [Remove-SpotifyTracksFromPlaylist](https://github.com/genXdev/GenXdev.Console/tree/main#remove-spotifytracksfromplaylist) | removefromplaylist | Removes tracks from a Spotify playlist. |
| [SayDate](https://github.com/genXdev/GenXdev.Console/tree/main#saydate) | &nbsp; | Speaks the current date using text-to-speech synthesis. |
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
| [Set-SpotifyPlaylistOrder](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyplaylistorder) | &nbsp; | &nbsp; |
| [Set-SpotifyPrevious](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyprevious) | prev, previous | Skips to the previous track in Spotify playback. |
| [Set-SpotifyRepeatContext](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyrepeatcontext) | repeat | Enables playlist repeat mode for Spotify playback. |
| [Set-SpotifyRepeatOff](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyrepeatoff) | norepeat, repeatoff | Disables Spotify repeat mode for the currently active device. |
| [Set-SpotifyRepeatSong](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyrepeatsong) | repeatsong | Enables song repeat mode in Spotify. |
| [Set-SpotifyShuffleOff](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyshuffleoff) | noshuffle, shuffleoff | Disables Spotify song-shuffle mode on the active device. |
| [Set-SpotifyShuffleOn](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifyshuffleon) | shuffle, shuffleon | Enables Spotify song-shuffle mode. |
| [Set-SpotifyStart](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifystart) | play, startmusic | Starts Spotify playback on the currently active device. |
| [Set-SpotifyStop](https://github.com/genXdev/GenXdev.Console/tree/main#set-spotifystop) | stop | Stops Spotify playback on the active device. |
| [Set-VLCPlayerFocused](https://github.com/genXdev/GenXdev.Console/tree/main#set-vlcplayerfocused) | fvlc, showvlc, vlcf | Sets focus to the VLC media player window. |
| [Start-TextToSpeech](https://github.com/genXdev/GenXdev.Console/tree/main#start-texttospeech) | say | Converts text to speech using the Windows Speech API. |
| [Start-VlcMediaPlayerNextInPlaylist](https://github.com/genXdev/GenXdev.Console/tree/main#start-vlcmediaplayernextinplaylist) | vlcnext | Advances VLC Media Player to the next item in the current playlist. |
| [Start-VlcMediaPlayerPreviousInPlaylist](https://github.com/genXdev/GenXdev.Console/tree/main#start-vlcmediaplayerpreviousinplaylist) | vlcback, vlcprev | Moves to the previous item in the VLC Media Player playlist. |
| [Stop-TextToSpeech](https://github.com/genXdev/GenXdev.Console/tree/main#stop-texttospeech) | sst | Immediately stops any ongoing text-to-speech output. |
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
| [EnsureSQLiteStudioInstalled](https://github.com/genXdev/GenXdev.Data/tree/main#ensuresqlitestudioinstalled) | &nbsp; | Ensures SQLiteStudio is installed and accessible from the command line. |
| [EnsureSSMSInstalled](https://github.com/genXdev/GenXdev.Data/tree/main#ensuressmsinstalled) | &nbsp; | Ensures SSMS is installed and accessible from the command line. |
| [Get-GenXdevPreference](https://github.com/genXdev/GenXdev.Data/tree/main#get-genxdevpreference) | getPreference | Retrieves a preference value from the GenXdev preferences store. |
| [Get-GenXdevPreferenceNames](https://github.com/genXdev/GenXdev.Data/tree/main#get-genxdevpreferencenames) | getPreferenceNames | Gets all preference names from session storage and database stores. |
| [Get-GenXdevPreferencesDatabasePath](https://github.com/genXdev/GenXdev.Data/tree/main#get-genxdevpreferencesdatabasepath) | &nbsp; | Gets the configured database path for preference data files used in GenXdev.Data operations. |
| [Get-KeyValueStoreNames](https://github.com/genXdev/GenXdev.Data/tree/main#get-keyvaluestorenames) | getstorenames | &nbsp; |
| [Get-SQLiteSchema](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqliteschema) | &nbsp; | Retrieves the complete schema information from a SQLite database. |
| [Get-SQLiteTableColumnData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetablecolumndata) | &nbsp; | Retrieves data from a specific column in a SQLite database table. |
| [Get-SQLiteTableData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetabledata) | &nbsp; | Retrieves data from a SQLite database table with optional record limiting. |
| [Get-SQLiteTables](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetables) | &nbsp; | Retrieves a list of table names from a SQLite database. |
| [Get-SQLiteTableSchema](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetableschema) | &nbsp; | Retrieves the schema information for a specified SQLite table. |
| [Get-SQLiteTransaction](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetransaction) | &nbsp; | Creates and returns a SQLite transaction object for batch operations. |
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
| [GetStoreFilePath](https://github.com/genXdev/GenXdev.Data/tree/main#getstorefilepath) | &nbsp; | &nbsp; |
| [Initialize-KeyValueStores](https://github.com/genXdev/GenXdev.Data/tree/main#initialize-keyvaluestores) | &nbsp; | Initializes KeyValueStore directory structure for local and OneDrive storage. |
| [Invoke-SQLiteQuery](https://github.com/genXdev/GenXdev.Data/tree/main#invoke-sqlitequery) | &nbsp; | Executes one or more SQL queries against a SQLite database with transaction support. |
| [Invoke-SQLiteStudio](https://github.com/genXdev/GenXdev.Data/tree/main#invoke-sqlitestudio) | &nbsp; | Executes SQLite database queries with support for parameters and transactions. |
| [Invoke-SqlServerQuery](https://github.com/genXdev/GenXdev.Data/tree/main#invoke-sqlserverquery) | &nbsp; | Executes one or more SQL queries against a SQL Server database with transaction support. |
| [Invoke-SSMS](https://github.com/genXdev/GenXdev.Data/tree/main#invoke-ssms) | sqlservermanagementstudio, ssms | Executes SQL Server database queries with support for parameters and transactions. |
| [New-SQLiteDatabase](https://github.com/genXdev/GenXdev.Data/tree/main#new-sqlitedatabase) | &nbsp; | Creates a new SQLite database file. |
| [New-SQLServerDatabase](https://github.com/genXdev/GenXdev.Data/tree/main#new-sqlserverdatabase) | nsqldb | Creates a new SQL Server database. |
| [Remove-GenXdevPreference](https://github.com/genXdev/GenXdev.Data/tree/main#remove-genxdevpreference) | removePreference | Removes a preference value from the GenXdev preferences store. |
| [Remove-KeyFromStore](https://github.com/genXdev/GenXdev.Data/tree/main#remove-keyfromstore) | removekey | &nbsp; |
| [Remove-KeyValueStore](https://github.com/genXdev/GenXdev.Data/tree/main#remove-keyvaluestore) | &nbsp; | &nbsp; |
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
| [EnsureSQLiteStudioInstalled](https://github.com/genXdev/GenXdev.Data/tree/main#ensuresqlitestudioinstalled) | &nbsp; | Ensures SQLiteStudio is installed and accessible from the command line. |
| [EnsureSSMSInstalled](https://github.com/genXdev/GenXdev.Data/tree/main#ensuressmsinstalled) | &nbsp; | Ensures SSMS is installed and accessible from the command line. |
| [Get-GenXdevPreference](https://github.com/genXdev/GenXdev.Data/tree/main#get-genxdevpreference) | getPreference | Retrieves a preference value from the GenXdev preferences store. |
| [Get-GenXdevPreferenceNames](https://github.com/genXdev/GenXdev.Data/tree/main#get-genxdevpreferencenames) | getPreferenceNames | Gets all preference names from session storage and database stores. |
| [Get-GenXdevPreferencesDatabasePath](https://github.com/genXdev/GenXdev.Data/tree/main#get-genxdevpreferencesdatabasepath) | &nbsp; | Gets the configured database path for preference data files used in GenXdev.Data operations. |
| [Get-KeyValueStoreNames](https://github.com/genXdev/GenXdev.Data/tree/main#get-keyvaluestorenames) | getstorenames | &nbsp; |
| [Get-SQLiteSchema](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqliteschema) | &nbsp; | Retrieves the complete schema information from a SQLite database. |
| [Get-SQLiteTableColumnData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetablecolumndata) | &nbsp; | Retrieves data from a specific column in a SQLite database table. |
| [Get-SQLiteTableData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetabledata) | &nbsp; | Retrieves data from a SQLite database table with optional record limiting. |
| [Get-SQLiteTables](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetables) | &nbsp; | Retrieves a list of table names from a SQLite database. |
| [Get-SQLiteTableSchema](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetableschema) | &nbsp; | Retrieves the schema information for a specified SQLite table. |
| [Get-SQLiteTransaction](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetransaction) | &nbsp; | Creates and returns a SQLite transaction object for batch operations. |
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
| [GetStoreFilePath](https://github.com/genXdev/GenXdev.Data/tree/main#getstorefilepath) | &nbsp; | &nbsp; |
| [Initialize-KeyValueStores](https://github.com/genXdev/GenXdev.Data/tree/main#initialize-keyvaluestores) | &nbsp; | Initializes KeyValueStore directory structure for local and OneDrive storage. |
| [Invoke-SQLiteQuery](https://github.com/genXdev/GenXdev.Data/tree/main#invoke-sqlitequery) | &nbsp; | Executes one or more SQL queries against a SQLite database with transaction support. |
| [Invoke-SQLiteStudio](https://github.com/genXdev/GenXdev.Data/tree/main#invoke-sqlitestudio) | &nbsp; | Executes SQLite database queries with support for parameters and transactions. |
| [Invoke-SqlServerQuery](https://github.com/genXdev/GenXdev.Data/tree/main#invoke-sqlserverquery) | &nbsp; | Executes one or more SQL queries against a SQL Server database with transaction support. |
| [Invoke-SSMS](https://github.com/genXdev/GenXdev.Data/tree/main#invoke-ssms) | sqlservermanagementstudio, ssms | Executes SQL Server database queries with support for parameters and transactions. |
| [New-SQLiteDatabase](https://github.com/genXdev/GenXdev.Data/tree/main#new-sqlitedatabase) | &nbsp; | Creates a new SQLite database file. |
| [New-SQLServerDatabase](https://github.com/genXdev/GenXdev.Data/tree/main#new-sqlserverdatabase) | nsqldb | Creates a new SQL Server database. |
| [Remove-GenXdevPreference](https://github.com/genXdev/GenXdev.Data/tree/main#remove-genxdevpreference) | removePreference | Removes a preference value from the GenXdev preferences store. |
| [Remove-KeyFromStore](https://github.com/genXdev/GenXdev.Data/tree/main#remove-keyfromstore) | removekey | &nbsp; |
| [Remove-KeyValueStore](https://github.com/genXdev/GenXdev.Data/tree/main#remove-keyvaluestore) | &nbsp; | &nbsp; |
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
| [EnsureSQLiteStudioInstalled](https://github.com/genXdev/GenXdev.Data/tree/main#ensuresqlitestudioinstalled) | &nbsp; | Ensures SQLiteStudio is installed and accessible from the command line. |
| [EnsureSSMSInstalled](https://github.com/genXdev/GenXdev.Data/tree/main#ensuressmsinstalled) | &nbsp; | Ensures SSMS is installed and accessible from the command line. |
| [Get-GenXdevPreference](https://github.com/genXdev/GenXdev.Data/tree/main#get-genxdevpreference) | getPreference | Retrieves a preference value from the GenXdev preferences store. |
| [Get-GenXdevPreferenceNames](https://github.com/genXdev/GenXdev.Data/tree/main#get-genxdevpreferencenames) | getPreferenceNames | Gets all preference names from session storage and database stores. |
| [Get-GenXdevPreferencesDatabasePath](https://github.com/genXdev/GenXdev.Data/tree/main#get-genxdevpreferencesdatabasepath) | &nbsp; | Gets the configured database path for preference data files used in GenXdev.Data operations. |
| [Get-KeyValueStoreNames](https://github.com/genXdev/GenXdev.Data/tree/main#get-keyvaluestorenames) | getstorenames | &nbsp; |
| [Get-SQLiteSchema](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqliteschema) | &nbsp; | Retrieves the complete schema information from a SQLite database. |
| [Get-SQLiteTableColumnData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetablecolumndata) | &nbsp; | Retrieves data from a specific column in a SQLite database table. |
| [Get-SQLiteTableData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetabledata) | &nbsp; | Retrieves data from a SQLite database table with optional record limiting. |
| [Get-SQLiteTables](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetables) | &nbsp; | Retrieves a list of table names from a SQLite database. |
| [Get-SQLiteTableSchema](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetableschema) | &nbsp; | Retrieves the schema information for a specified SQLite table. |
| [Get-SQLiteTransaction](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetransaction) | &nbsp; | Creates and returns a SQLite transaction object for batch operations. |
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
| [GetStoreFilePath](https://github.com/genXdev/GenXdev.Data/tree/main#getstorefilepath) | &nbsp; | &nbsp; |
| [Initialize-KeyValueStores](https://github.com/genXdev/GenXdev.Data/tree/main#initialize-keyvaluestores) | &nbsp; | Initializes KeyValueStore directory structure for local and OneDrive storage. |
| [Invoke-SQLiteQuery](https://github.com/genXdev/GenXdev.Data/tree/main#invoke-sqlitequery) | &nbsp; | Executes one or more SQL queries against a SQLite database with transaction support. |
| [Invoke-SQLiteStudio](https://github.com/genXdev/GenXdev.Data/tree/main#invoke-sqlitestudio) | &nbsp; | Executes SQLite database queries with support for parameters and transactions. |
| [Invoke-SqlServerQuery](https://github.com/genXdev/GenXdev.Data/tree/main#invoke-sqlserverquery) | &nbsp; | Executes one or more SQL queries against a SQL Server database with transaction support. |
| [Invoke-SSMS](https://github.com/genXdev/GenXdev.Data/tree/main#invoke-ssms) | sqlservermanagementstudio, ssms | Executes SQL Server database queries with support for parameters and transactions. |
| [New-SQLiteDatabase](https://github.com/genXdev/GenXdev.Data/tree/main#new-sqlitedatabase) | &nbsp; | Creates a new SQLite database file. |
| [New-SQLServerDatabase](https://github.com/genXdev/GenXdev.Data/tree/main#new-sqlserverdatabase) | nsqldb | Creates a new SQL Server database. |
| [Remove-GenXdevPreference](https://github.com/genXdev/GenXdev.Data/tree/main#remove-genxdevpreference) | removePreference | Removes a preference value from the GenXdev preferences store. |
| [Remove-KeyFromStore](https://github.com/genXdev/GenXdev.Data/tree/main#remove-keyfromstore) | removekey | &nbsp; |
| [Remove-KeyValueStore](https://github.com/genXdev/GenXdev.Data/tree/main#remove-keyvaluestore) | &nbsp; | &nbsp; |
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
| [EnsureSQLiteStudioInstalled](https://github.com/genXdev/GenXdev.Data/tree/main#ensuresqlitestudioinstalled) | &nbsp; | Ensures SQLiteStudio is installed and accessible from the command line. |
| [EnsureSSMSInstalled](https://github.com/genXdev/GenXdev.Data/tree/main#ensuressmsinstalled) | &nbsp; | Ensures SSMS is installed and accessible from the command line. |
| [Get-GenXdevPreference](https://github.com/genXdev/GenXdev.Data/tree/main#get-genxdevpreference) | getPreference | Retrieves a preference value from the GenXdev preferences store. |
| [Get-GenXdevPreferenceNames](https://github.com/genXdev/GenXdev.Data/tree/main#get-genxdevpreferencenames) | getPreferenceNames | Gets all preference names from session storage and database stores. |
| [Get-GenXdevPreferencesDatabasePath](https://github.com/genXdev/GenXdev.Data/tree/main#get-genxdevpreferencesdatabasepath) | &nbsp; | Gets the configured database path for preference data files used in GenXdev.Data operations. |
| [Get-KeyValueStoreNames](https://github.com/genXdev/GenXdev.Data/tree/main#get-keyvaluestorenames) | getstorenames | &nbsp; |
| [Get-SQLiteSchema](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqliteschema) | &nbsp; | Retrieves the complete schema information from a SQLite database. |
| [Get-SQLiteTableColumnData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetablecolumndata) | &nbsp; | Retrieves data from a specific column in a SQLite database table. |
| [Get-SQLiteTableData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetabledata) | &nbsp; | Retrieves data from a SQLite database table with optional record limiting. |
| [Get-SQLiteTables](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetables) | &nbsp; | Retrieves a list of table names from a SQLite database. |
| [Get-SQLiteTableSchema](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetableschema) | &nbsp; | Retrieves the schema information for a specified SQLite table. |
| [Get-SQLiteTransaction](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetransaction) | &nbsp; | Creates and returns a SQLite transaction object for batch operations. |
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
| [GetStoreFilePath](https://github.com/genXdev/GenXdev.Data/tree/main#getstorefilepath) | &nbsp; | &nbsp; |
| [Initialize-KeyValueStores](https://github.com/genXdev/GenXdev.Data/tree/main#initialize-keyvaluestores) | &nbsp; | Initializes KeyValueStore directory structure for local and OneDrive storage. |
| [Invoke-SQLiteQuery](https://github.com/genXdev/GenXdev.Data/tree/main#invoke-sqlitequery) | &nbsp; | Executes one or more SQL queries against a SQLite database with transaction support. |
| [Invoke-SQLiteStudio](https://github.com/genXdev/GenXdev.Data/tree/main#invoke-sqlitestudio) | &nbsp; | Executes SQLite database queries with support for parameters and transactions. |
| [Invoke-SqlServerQuery](https://github.com/genXdev/GenXdev.Data/tree/main#invoke-sqlserverquery) | &nbsp; | Executes one or more SQL queries against a SQL Server database with transaction support. |
| [Invoke-SSMS](https://github.com/genXdev/GenXdev.Data/tree/main#invoke-ssms) | sqlservermanagementstudio, ssms | Executes SQL Server database queries with support for parameters and transactions. |
| [New-SQLiteDatabase](https://github.com/genXdev/GenXdev.Data/tree/main#new-sqlitedatabase) | &nbsp; | Creates a new SQLite database file. |
| [New-SQLServerDatabase](https://github.com/genXdev/GenXdev.Data/tree/main#new-sqlserverdatabase) | nsqldb | Creates a new SQL Server database. |
| [Remove-GenXdevPreference](https://github.com/genXdev/GenXdev.Data/tree/main#remove-genxdevpreference) | removePreference | Removes a preference value from the GenXdev preferences store. |
| [Remove-KeyFromStore](https://github.com/genXdev/GenXdev.Data/tree/main#remove-keyfromstore) | removekey | &nbsp; |
| [Remove-KeyValueStore](https://github.com/genXdev/GenXdev.Data/tree/main#remove-keyvaluestore) | &nbsp; | &nbsp; |
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
| [EnsureSQLiteStudioInstalled](https://github.com/genXdev/GenXdev.Data/tree/main#ensuresqlitestudioinstalled) | &nbsp; | Ensures SQLiteStudio is installed and accessible from the command line. |
| [EnsureSSMSInstalled](https://github.com/genXdev/GenXdev.Data/tree/main#ensuressmsinstalled) | &nbsp; | Ensures SSMS is installed and accessible from the command line. |
| [Get-GenXdevPreference](https://github.com/genXdev/GenXdev.Data/tree/main#get-genxdevpreference) | getPreference | Retrieves a preference value from the GenXdev preferences store. |
| [Get-GenXdevPreferenceNames](https://github.com/genXdev/GenXdev.Data/tree/main#get-genxdevpreferencenames) | getPreferenceNames | Gets all preference names from session storage and database stores. |
| [Get-GenXdevPreferencesDatabasePath](https://github.com/genXdev/GenXdev.Data/tree/main#get-genxdevpreferencesdatabasepath) | &nbsp; | Gets the configured database path for preference data files used in GenXdev.Data operations. |
| [Get-KeyValueStoreNames](https://github.com/genXdev/GenXdev.Data/tree/main#get-keyvaluestorenames) | getstorenames | &nbsp; |
| [Get-SQLiteSchema](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqliteschema) | &nbsp; | Retrieves the complete schema information from a SQLite database. |
| [Get-SQLiteTableColumnData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetablecolumndata) | &nbsp; | Retrieves data from a specific column in a SQLite database table. |
| [Get-SQLiteTableData](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetabledata) | &nbsp; | Retrieves data from a SQLite database table with optional record limiting. |
| [Get-SQLiteTables](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetables) | &nbsp; | Retrieves a list of table names from a SQLite database. |
| [Get-SQLiteTableSchema](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetableschema) | &nbsp; | Retrieves the schema information for a specified SQLite table. |
| [Get-SQLiteTransaction](https://github.com/genXdev/GenXdev.Data/tree/main#get-sqlitetransaction) | &nbsp; | Creates and returns a SQLite transaction object for batch operations. |
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
| [GetStoreFilePath](https://github.com/genXdev/GenXdev.Data/tree/main#getstorefilepath) | &nbsp; | &nbsp; |
| [Initialize-KeyValueStores](https://github.com/genXdev/GenXdev.Data/tree/main#initialize-keyvaluestores) | &nbsp; | Initializes KeyValueStore directory structure for local and OneDrive storage. |
| [Invoke-SQLiteQuery](https://github.com/genXdev/GenXdev.Data/tree/main#invoke-sqlitequery) | &nbsp; | Executes one or more SQL queries against a SQLite database with transaction support. |
| [Invoke-SQLiteStudio](https://github.com/genXdev/GenXdev.Data/tree/main#invoke-sqlitestudio) | &nbsp; | Executes SQLite database queries with support for parameters and transactions. |
| [Invoke-SqlServerQuery](https://github.com/genXdev/GenXdev.Data/tree/main#invoke-sqlserverquery) | &nbsp; | Executes one or more SQL queries against a SQL Server database with transaction support. |
| [Invoke-SSMS](https://github.com/genXdev/GenXdev.Data/tree/main#invoke-ssms) | sqlservermanagementstudio, ssms | Executes SQL Server database queries with support for parameters and transactions. |
| [New-SQLiteDatabase](https://github.com/genXdev/GenXdev.Data/tree/main#new-sqlitedatabase) | &nbsp; | Creates a new SQLite database file. |
| [New-SQLServerDatabase](https://github.com/genXdev/GenXdev.Data/tree/main#new-sqlserverdatabase) | nsqldb | Creates a new SQL Server database. |
| [Remove-GenXdevPreference](https://github.com/genXdev/GenXdev.Data/tree/main#remove-genxdevpreference) | removePreference | Removes a preference value from the GenXdev preferences store. |
| [Remove-KeyFromStore](https://github.com/genXdev/GenXdev.Data/tree/main#remove-keyfromstore) | removekey | &nbsp; |
| [Remove-KeyValueStore](https://github.com/genXdev/GenXdev.Data/tree/main#remove-keyvaluestore) | &nbsp; | &nbsp; |
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
| [EnsurePester](https://github.com/genXdev/GenXdev.FileSystem/tree/main#ensurepester) | &nbsp; | Ensures Pester testing framework is available for use. |
| [Expand-Path](https://github.com/genXdev/GenXdev.FileSystem/tree/main#expand-path) | ep | Expands any given file reference to a full pathname. |
| [Find-DuplicateFiles](https://github.com/genXdev/GenXdev.FileSystem/tree/main#find-duplicatefiles) | fdf | Find duplicate files across multiple directories based on configurable criteria. |
| [Find-Item](https://github.com/genXdev/GenXdev.FileSystem/tree/main#find-item) | l | Fast multi-threaded file and directory search with optional textcontent pattern matching |
| [Invoke-Fasti](https://github.com/genXdev/GenXdev.FileSystem/tree/main#invoke-fasti) | fasti | &nbsp; |
| [Move-ItemWithTracking](https://github.com/genXdev/GenXdev.FileSystem/tree/main#move-itemwithtracking) | &nbsp; | Moves files and directories while preserving filesystem links and references. |
| [Move-ToRecycleBin](https://github.com/genXdev/GenXdev.FileSystem/tree/main#move-torecyclebin) | recycle | Moves files and directories to the Windows Recycle Bin safely. |
| [ReadJsonWithRetry](https://github.com/genXdev/GenXdev.FileSystem/tree/main#readjsonwithretry) | &nbsp; | Reads JSON file with retry logic and automatic lock cleanup. |
| [Remove-AllItems](https://github.com/genXdev/GenXdev.FileSystem/tree/main#remove-allitems) | sdel | Recursively removes all content from a directory with advanced error handling. |
| [Remove-ItemWithFallback](https://github.com/genXdev/GenXdev.FileSystem/tree/main#remove-itemwithfallback) | rmf | Removes files or directories with multiple fallback mechanisms for reliable deletion. |
| [Remove-OnReboot](https://github.com/genXdev/GenXdev.FileSystem/tree/main#remove-onreboot) | &nbsp; | Marks files or directories for deletion during the next system boot. |
| [Rename-InProject](https://github.com/genXdev/GenXdev.FileSystem/tree/main#rename-inproject) | rip | Performs text replacement throughout a project directory. |
| [ResolveInputObjectFileNames](https://github.com/genXdev/GenXdev.FileSystem/tree/main#resolveinputobjectfilenames) | &nbsp; | &nbsp; |
| [Set-FoundLocation](https://github.com/genXdev/GenXdev.FileSystem/tree/main#set-foundlocation) | lcd | Finds the first matching file or folder and sets the location to it. |
| [Set-LocationParent](https://github.com/genXdev/GenXdev.FileSystem/tree/main#set-locationparent) | .. | Changes the current location to the parent directory and lists its contents. |
| [Set-LocationParent2](https://github.com/genXdev/GenXdev.FileSystem/tree/main#set-locationparent2) | ... | Navigates up two directory levels in the file system hierarchy. |
| [Set-LocationParent3](https://github.com/genXdev/GenXdev.FileSystem/tree/main#set-locationparent3) | .... | Navigates up three directory levels in the file system hierarchy. |
| [Set-LocationParent4](https://github.com/genXdev/GenXdev.FileSystem/tree/main#set-locationparent4) | ..... | Navigates up four directory levels in the filesystem hierarchy. |
| [Set-LocationParent5](https://github.com/genXdev/GenXdev.FileSystem/tree/main#set-locationparent5) | ...... | Navigates up five directory levels in the file system hierarchy. |
| [Start-RoboCopy](https://github.com/genXdev/GenXdev.FileSystem/tree/main#start-robocopy) | rc, xc | Provides a PowerShell wrapper for Microsoft's Robust Copy (RoboCopy) utility. |
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
| [ConvertTo-HashTable](https://github.com/genXdev/GenXdev.Helpers/tree/main#convertto-hashtable) | &nbsp; | Converts a PSCustomObject to a HashTable recursively. |
| [ConvertTo-JsonEx](https://github.com/genXdev/GenXdev.Helpers/tree/main#convertto-jsonex) | tojsonex | Converts an object to a JSON string with extended options. |
| [EnsureGenXdev](https://github.com/genXdev/GenXdev.Helpers/tree/main#ensuregenxdev) | &nbsp; | &nbsp; |
| [EnsureNuGetAssembly](https://github.com/genXdev/GenXdev.Helpers/tree/main#ensurenugetassembly) | &nbsp; | Downloads and loads .NET assemblies from NuGet packages based on package key or ID. |
| [Get-DefaultWebLanguage](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-defaultweblanguage) | &nbsp; | Gets the default web language key based on the system's current language settings. |
| [Get-FreeFallHeight](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-freefallheight) | &nbsp; | Calculates the height fallen during free fall for a given time duration. |
| [Get-FreeFallTime](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-freefalltime) | &nbsp; | Calculates the time it takes for an object to fall a specified distance. |
| [Get-GenXDevCmdlet](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-genxdevcmdlet) | gcmds | Retrieves and lists all GenXdev cmdlets and their details. |
| [Get-ImageGeolocation](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-imagegeolocation) | &nbsp; | Extracts geolocation data from an image file. |
| [Get-ImageMetadata](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-imagemetadata) | &nbsp; | Extracts comprehensive metadata from an image file. |
| [Get-WebLanguageDictionary](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-weblanguagedictionary) | &nbsp; | Returns a reversed dictionary for all languages supported by Google Search |
| [Import-GenXdevModules](https://github.com/genXdev/GenXdev.Helpers/tree/main#import-genxdevmodules) | reloadgenxdev | Imports all GenXdev PowerShell modules into the global scope. |
| [Initialize-SearchPaths](https://github.com/genXdev/GenXdev.Helpers/tree/main#initialize-searchpaths) | &nbsp; | Initializes and configures system search paths for package management. |
| [Invoke-OnEachGenXdevModule](https://github.com/genXdev/GenXdev.Helpers/tree/main#invoke-oneachgenxdevmodule) | foreach-genxdev-module-do | Executes a script block on each GenXdev module in the workspace. |
| [Out-Serial](https://github.com/genXdev/GenXdev.Helpers/tree/main#out-serial) | &nbsp; | Sends a string to a serial port |
| [Remove-JSONComments](https://github.com/genXdev/GenXdev.Helpers/tree/main#remove-jsoncomments) | &nbsp; | Removes comments from JSON content. |
| [resetdefaultmonitor](https://github.com/genXdev/GenXdev.Helpers/tree/main#resetdefaultmonitor) | &nbsp; | Restores default secondary monitor configuration. |
| [SecondScreen](https://github.com/genXdev/GenXdev.Helpers/tree/main#secondscreen) | &nbsp; | Sets default second-monitor configuration. |
| [Show-GenXDevCmdlet](https://github.com/genXdev/GenXdev.Helpers/tree/main#show-genxdevcmdlet) | cmds | Displays GenXdev PowerShell modules with their cmdlets and aliases. |
| [Show-Verb](https://github.com/genXdev/GenXdev.Helpers/tree/main#show-verb) | showverbs | Shows a short alphabetical list of all PowerShell verbs. |
| [SideBySide](https://github.com/genXdev/GenXdev.Helpers/tree/main#sidebyside) | &nbsp; | Sets default side-by-side configuration. |
| [Test-UnattendedMode](https://github.com/genXdev/GenXdev.Helpers/tree/main#test-unattendedmode) | &nbsp; | Detects if PowerShell is running in unattended/automated mode |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Helpers.Math.Physics

**A Windows PowerShell module with helpers mostly used by other GenXdev modules**

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [_EnsureTypes](https://github.com/genXdev/GenXdev.Helpers/tree/main#ensuretypes) | &nbsp; | &nbsp; |
| [alignScript](https://github.com/genXdev/GenXdev.Helpers/tree/main#alignscript) | &nbsp; | Returns a string (with altered indentation) of a provided scriptblock string |
| [ConvertTo-HashTable](https://github.com/genXdev/GenXdev.Helpers/tree/main#convertto-hashtable) | &nbsp; | Converts a PSCustomObject to a HashTable recursively. |
| [ConvertTo-JsonEx](https://github.com/genXdev/GenXdev.Helpers/tree/main#convertto-jsonex) | tojsonex | Converts an object to a JSON string with extended options. |
| [EnsureGenXdev](https://github.com/genXdev/GenXdev.Helpers/tree/main#ensuregenxdev) | &nbsp; | &nbsp; |
| [EnsureNuGetAssembly](https://github.com/genXdev/GenXdev.Helpers/tree/main#ensurenugetassembly) | &nbsp; | Downloads and loads .NET assemblies from NuGet packages based on package key or ID. |
| [Get-DefaultWebLanguage](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-defaultweblanguage) | &nbsp; | Gets the default web language key based on the system's current language settings. |
| [Get-FreeFallHeight](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-freefallheight) | &nbsp; | Calculates the height fallen during free fall for a given time duration. |
| [Get-FreeFallTime](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-freefalltime) | &nbsp; | Calculates the time it takes for an object to fall a specified distance. |
| [Get-GenXDevCmdlet](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-genxdevcmdlet) | gcmds | Retrieves and lists all GenXdev cmdlets and their details. |
| [Get-ImageGeolocation](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-imagegeolocation) | &nbsp; | Extracts geolocation data from an image file. |
| [Get-ImageMetadata](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-imagemetadata) | &nbsp; | Extracts comprehensive metadata from an image file. |
| [Get-WebLanguageDictionary](https://github.com/genXdev/GenXdev.Helpers/tree/main#get-weblanguagedictionary) | &nbsp; | Returns a reversed dictionary for all languages supported by Google Search |
| [Import-GenXdevModules](https://github.com/genXdev/GenXdev.Helpers/tree/main#import-genxdevmodules) | reloadgenxdev | Imports all GenXdev PowerShell modules into the global scope. |
| [Initialize-SearchPaths](https://github.com/genXdev/GenXdev.Helpers/tree/main#initialize-searchpaths) | &nbsp; | Initializes and configures system search paths for package management. |
| [Invoke-OnEachGenXdevModule](https://github.com/genXdev/GenXdev.Helpers/tree/main#invoke-oneachgenxdevmodule) | foreach-genxdev-module-do | Executes a script block on each GenXdev module in the workspace. |
| [Out-Serial](https://github.com/genXdev/GenXdev.Helpers/tree/main#out-serial) | &nbsp; | Sends a string to a serial port |
| [Remove-JSONComments](https://github.com/genXdev/GenXdev.Helpers/tree/main#remove-jsoncomments) | &nbsp; | Removes comments from JSON content. |
| [resetdefaultmonitor](https://github.com/genXdev/GenXdev.Helpers/tree/main#resetdefaultmonitor) | &nbsp; | Restores default secondary monitor configuration. |
| [SecondScreen](https://github.com/genXdev/GenXdev.Helpers/tree/main#secondscreen) | &nbsp; | Sets default second-monitor configuration. |
| [Show-GenXDevCmdlet](https://github.com/genXdev/GenXdev.Helpers/tree/main#show-genxdevcmdlet) | cmds | Displays GenXdev PowerShell modules with their cmdlets and aliases. |
| [Show-Verb](https://github.com/genXdev/GenXdev.Helpers/tree/main#show-verb) | showverbs | Shows a short alphabetical list of all PowerShell verbs. |
| [SideBySide](https://github.com/genXdev/GenXdev.Helpers/tree/main#sidebyside) | &nbsp; | Sets default side-by-side configuration. |
| [Test-UnattendedMode](https://github.com/genXdev/GenXdev.Helpers/tree/main#test-unattendedmode) | &nbsp; | Detects if PowerShell is running in unattended/automated mode |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Helpers/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Media

**A Windows PowerShell module that helps with converting media files like pictures and video files**

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [EnsureYtdlp](https://github.com/genXdev/GenXdev.Media/tree/main#ensureytdlp) | &nbsp; | Ensures yt-dlp is installed and available in the default WSL image. |
| [Invoke-YTDlpSaveVideo](https://github.com/genXdev/GenXdev.Media/tree/main#invoke-ytdlpsavevideo) | savevideo | Downloads a video from a specified URL using yt-dlp and saves metadata. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Media/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Media.ffmpeg

**A Windows PowerShell module that helps with converting media files like pictures and video files**

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [EnsureYtdlp](https://github.com/genXdev/GenXdev.Media/tree/main#ensureytdlp) | &nbsp; | Ensures yt-dlp is installed and available in the default WSL image. |
| [Invoke-YTDlpSaveVideo](https://github.com/genXdev/GenXdev.Media/tree/main#invoke-ytdlpsavevideo) | savevideo | Downloads a video from a specified URL using yt-dlp and saves metadata. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Media/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Media.ytdlp

**A Windows PowerShell module that helps with converting media files like pictures and video files**

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [EnsureYtdlp](https://github.com/genXdev/GenXdev.Media/tree/main#ensureytdlp) | &nbsp; | Ensures yt-dlp is installed and available in the default WSL image. |
| [Invoke-YTDlpSaveVideo](https://github.com/genXdev/GenXdev.Media/tree/main#invoke-ytdlpsavevideo) | savevideo | Downloads a video from a specified URL using yt-dlp and saves metadata. |

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
| [Invoke-WebbrowserTabPollingScript](https://github.com/genXdev/GenXdev.Queries/tree/main#invoke-webbrowsertabpollingscript) | &nbsp; | Executes a background polling script in a previously selected webbrowser tab. |
| [Open-AllGoogleLinks](https://github.com/genXdev/GenXdev.Queries/tree/main#open-allgooglelinks) | qlinks | Performs an infinite auto opening google search . |
| [Open-AllPossibleQueries](https://github.com/genXdev/GenXdev.Queries/tree/main#open-allpossiblequeries) | qq | Opens all possible query types for given search terms or URLs. |
| [Open-AllPossibleTextQueries](https://github.com/genXdev/GenXdev.Queries/tree/main#open-allpossibletextqueries) | qqq | Executes all Text query Cmdlets in parallel and displays results. |
| [Open-AllYoutubeVideos](https://github.com/genXdev/GenXdev.Queries/tree/main#open-allyoutubevideos) | qvideos, qyt | Opens and controls YouTube videos in a browser window with keyboard shortcuts. |
| [Open-BingCopilotQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-bingcopilotquery) | aibc | Opens a Bing CoPilot query in a webbrowser |
| [Open-BingQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-bingquery) | bq | Opens a Bing search query in a web browser. |
| [Open-BuiltWithSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-builtwithsiteinfo) | &nbsp; | Opens BuiltWith website queries in a web browser. |
| [Open-ChatGPTQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-chatgptquery) | aicgpt, askchatgpt | Opens a ChatGPT query in a web browser. |
| [Open-CloudLLMChat](https://github.com/genXdev/GenXdev.Queries/tree/main#open-cloudllmchat) | ask | Opens a cloud LLM chat interface for AI queries. |
| [Open-DeepSearchQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-deepsearchquery) | aideepseek, askdeepsearch | Opens a DeepSeek query in a webbrowser |
| [Open-GameOfLife](https://github.com/genXdev/GenXdev.Queries/tree/main#open-gameoflife) | conway, gameoflife | Opens Conway's Game of Life simulation in a web browser. |
| [Open-GenXdevAppCatalog](https://github.com/genXdev/GenXdev.Queries/tree/main#open-genxdevappcatalog) | appcatalog | Opens the GenXdev progressive webapps catalog in a web browser. |
| [Open-GithubCopilotQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-githubcopilotquery) | aigc, askghcopilot | Opens a Github CoPilot query in a webbrowser |
| [Open-GithubQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-githubquery) | qgh, qgithub | &nbsp; |
| [Open-GoogleGeminiQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-googlegeminiquery) | aigg, askgemini | Opens a Google Gemini query in a webbrowser |
| [Open-GoogleQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-googlequery) | &nbsp; | &nbsp; |
| [Open-GoogleSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-googlesiteinfo) | &nbsp; | Opens Google site information queries in a web browser. |
| [Open-IMDBQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-imdbquery) | imdb | Opens an IMDB search query in a web browser. |
| [Open-InstantStreetViewQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-instantstreetviewquery) | isv | Opens InstantStreetView queries in a web browser. |
| [Open-MovieQuote](https://github.com/genXdev/GenXdev.Queries/tree/main#open-moviequote) | moviequote | Opens a video of a movie quote in a web browser. |
| [Open-SearchEngine](https://github.com/genXdev/GenXdev.Queries/tree/main#open-searchengine) | q | Opens a search query in the specified search engine using a web browser. |
| [Open-SimularWebSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-simularwebsiteinfo) | simularsite | Opens SimilarWeb website information for specified URLs in a web browser. |
| [Open-StackOverflowQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-stackoverflowquery) | qso | Opens Stack Overflow search queries in a web browser. |
| [Open-Timeline](https://github.com/genXdev/GenXdev.Queries/tree/main#open-timeline) | timeline | &nbsp; |
| [Open-ViralSimulation](https://github.com/genXdev/GenXdev.Queries/tree/main#open-viralsimulation) | viral | &nbsp; |
| [Open-WaybackMachineSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-waybackmachinesiteinfo) | wayback | Opens WaybackMachine site information in a web browser. |
| [Open-WebsiteAndPerformQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-websiteandperformquery) | owaq | Opens a webpage in a webbrowser and performs one or more queries. |
| [Open-WhoisHostSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-whoishostsiteinfo) | whois | Opens a Whois host information query in a web browser. |
| [Open-WikipediaNLQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-wikipedianlquery) | wikinl | Opens Dutch Wikipedia searches in a web browser. |
| [Open-WikipediaQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-wikipediaquery) | wiki | Opens a Wikipedia query in a webbrowser. |
| [Open-WolframAlphaQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-wolframalphaquery) | qalpha | Opens a Wolfram Alpha query in a web browser. |
| [Open-XGrokQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-xgrokquery) | aixg, askxgrok | Opens a X Grok query in a webbrowser |
| [Open-Yab](https://github.com/genXdev/GenXdev.Queries/tree/main#open-yab) | yab | Opens the YAB game in a web browser with configurable settings. |
| [Open-YabAIBattle](https://github.com/genXdev/GenXdev.Queries/tree/main#open-yabaibattle) | yabbattle | Opens the YabAI Battle game in a web browser. |
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
| [Invoke-WebbrowserTabPollingScript](https://github.com/genXdev/GenXdev.Queries/tree/main#invoke-webbrowsertabpollingscript) | &nbsp; | Executes a background polling script in a previously selected webbrowser tab. |
| [Open-AllGoogleLinks](https://github.com/genXdev/GenXdev.Queries/tree/main#open-allgooglelinks) | qlinks | Performs an infinite auto opening google search . |
| [Open-AllPossibleQueries](https://github.com/genXdev/GenXdev.Queries/tree/main#open-allpossiblequeries) | qq | Opens all possible query types for given search terms or URLs. |
| [Open-AllPossibleTextQueries](https://github.com/genXdev/GenXdev.Queries/tree/main#open-allpossibletextqueries) | qqq | Executes all Text query Cmdlets in parallel and displays results. |
| [Open-AllYoutubeVideos](https://github.com/genXdev/GenXdev.Queries/tree/main#open-allyoutubevideos) | qvideos, qyt | Opens and controls YouTube videos in a browser window with keyboard shortcuts. |
| [Open-BingCopilotQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-bingcopilotquery) | aibc | Opens a Bing CoPilot query in a webbrowser |
| [Open-BingQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-bingquery) | bq | Opens a Bing search query in a web browser. |
| [Open-BuiltWithSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-builtwithsiteinfo) | &nbsp; | Opens BuiltWith website queries in a web browser. |
| [Open-ChatGPTQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-chatgptquery) | aicgpt, askchatgpt | Opens a ChatGPT query in a web browser. |
| [Open-CloudLLMChat](https://github.com/genXdev/GenXdev.Queries/tree/main#open-cloudllmchat) | ask | Opens a cloud LLM chat interface for AI queries. |
| [Open-DeepSearchQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-deepsearchquery) | aideepseek, askdeepsearch | Opens a DeepSeek query in a webbrowser |
| [Open-GameOfLife](https://github.com/genXdev/GenXdev.Queries/tree/main#open-gameoflife) | conway, gameoflife | Opens Conway's Game of Life simulation in a web browser. |
| [Open-GenXdevAppCatalog](https://github.com/genXdev/GenXdev.Queries/tree/main#open-genxdevappcatalog) | appcatalog | Opens the GenXdev progressive webapps catalog in a web browser. |
| [Open-GithubCopilotQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-githubcopilotquery) | aigc, askghcopilot | Opens a Github CoPilot query in a webbrowser |
| [Open-GithubQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-githubquery) | qgh, qgithub | &nbsp; |
| [Open-GoogleGeminiQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-googlegeminiquery) | aigg, askgemini | Opens a Google Gemini query in a webbrowser |
| [Open-GoogleQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-googlequery) | &nbsp; | &nbsp; |
| [Open-GoogleSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-googlesiteinfo) | &nbsp; | Opens Google site information queries in a web browser. |
| [Open-IMDBQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-imdbquery) | imdb | Opens an IMDB search query in a web browser. |
| [Open-InstantStreetViewQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-instantstreetviewquery) | isv | Opens InstantStreetView queries in a web browser. |
| [Open-MovieQuote](https://github.com/genXdev/GenXdev.Queries/tree/main#open-moviequote) | moviequote | Opens a video of a movie quote in a web browser. |
| [Open-SearchEngine](https://github.com/genXdev/GenXdev.Queries/tree/main#open-searchengine) | q | Opens a search query in the specified search engine using a web browser. |
| [Open-SimularWebSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-simularwebsiteinfo) | simularsite | Opens SimilarWeb website information for specified URLs in a web browser. |
| [Open-StackOverflowQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-stackoverflowquery) | qso | Opens Stack Overflow search queries in a web browser. |
| [Open-Timeline](https://github.com/genXdev/GenXdev.Queries/tree/main#open-timeline) | timeline | &nbsp; |
| [Open-ViralSimulation](https://github.com/genXdev/GenXdev.Queries/tree/main#open-viralsimulation) | viral | &nbsp; |
| [Open-WaybackMachineSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-waybackmachinesiteinfo) | wayback | Opens WaybackMachine site information in a web browser. |
| [Open-WebsiteAndPerformQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-websiteandperformquery) | owaq | Opens a webpage in a webbrowser and performs one or more queries. |
| [Open-WhoisHostSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-whoishostsiteinfo) | whois | Opens a Whois host information query in a web browser. |
| [Open-WikipediaNLQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-wikipedianlquery) | wikinl | Opens Dutch Wikipedia searches in a web browser. |
| [Open-WikipediaQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-wikipediaquery) | wiki | Opens a Wikipedia query in a webbrowser. |
| [Open-WolframAlphaQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-wolframalphaquery) | qalpha | Opens a Wolfram Alpha query in a web browser. |
| [Open-XGrokQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-xgrokquery) | aixg, askxgrok | Opens a X Grok query in a webbrowser |
| [Open-Yab](https://github.com/genXdev/GenXdev.Queries/tree/main#open-yab) | yab | Opens the YAB game in a web browser with configurable settings. |
| [Open-YabAIBattle](https://github.com/genXdev/GenXdev.Queries/tree/main#open-yabaibattle) | yabbattle | Opens the YabAI Battle game in a web browser. |
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
| [Invoke-WebbrowserTabPollingScript](https://github.com/genXdev/GenXdev.Queries/tree/main#invoke-webbrowsertabpollingscript) | &nbsp; | Executes a background polling script in a previously selected webbrowser tab. |
| [Open-AllGoogleLinks](https://github.com/genXdev/GenXdev.Queries/tree/main#open-allgooglelinks) | qlinks | Performs an infinite auto opening google search . |
| [Open-AllPossibleQueries](https://github.com/genXdev/GenXdev.Queries/tree/main#open-allpossiblequeries) | qq | Opens all possible query types for given search terms or URLs. |
| [Open-AllPossibleTextQueries](https://github.com/genXdev/GenXdev.Queries/tree/main#open-allpossibletextqueries) | qqq | Executes all Text query Cmdlets in parallel and displays results. |
| [Open-AllYoutubeVideos](https://github.com/genXdev/GenXdev.Queries/tree/main#open-allyoutubevideos) | qvideos, qyt | Opens and controls YouTube videos in a browser window with keyboard shortcuts. |
| [Open-BingCopilotQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-bingcopilotquery) | aibc | Opens a Bing CoPilot query in a webbrowser |
| [Open-BingQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-bingquery) | bq | Opens a Bing search query in a web browser. |
| [Open-BuiltWithSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-builtwithsiteinfo) | &nbsp; | Opens BuiltWith website queries in a web browser. |
| [Open-ChatGPTQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-chatgptquery) | aicgpt, askchatgpt | Opens a ChatGPT query in a web browser. |
| [Open-CloudLLMChat](https://github.com/genXdev/GenXdev.Queries/tree/main#open-cloudllmchat) | ask | Opens a cloud LLM chat interface for AI queries. |
| [Open-DeepSearchQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-deepsearchquery) | aideepseek, askdeepsearch | Opens a DeepSeek query in a webbrowser |
| [Open-GameOfLife](https://github.com/genXdev/GenXdev.Queries/tree/main#open-gameoflife) | conway, gameoflife | Opens Conway's Game of Life simulation in a web browser. |
| [Open-GenXdevAppCatalog](https://github.com/genXdev/GenXdev.Queries/tree/main#open-genxdevappcatalog) | appcatalog | Opens the GenXdev progressive webapps catalog in a web browser. |
| [Open-GithubCopilotQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-githubcopilotquery) | aigc, askghcopilot | Opens a Github CoPilot query in a webbrowser |
| [Open-GithubQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-githubquery) | qgh, qgithub | &nbsp; |
| [Open-GoogleGeminiQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-googlegeminiquery) | aigg, askgemini | Opens a Google Gemini query in a webbrowser |
| [Open-GoogleQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-googlequery) | &nbsp; | &nbsp; |
| [Open-GoogleSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-googlesiteinfo) | &nbsp; | Opens Google site information queries in a web browser. |
| [Open-IMDBQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-imdbquery) | imdb | Opens an IMDB search query in a web browser. |
| [Open-InstantStreetViewQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-instantstreetviewquery) | isv | Opens InstantStreetView queries in a web browser. |
| [Open-MovieQuote](https://github.com/genXdev/GenXdev.Queries/tree/main#open-moviequote) | moviequote | Opens a video of a movie quote in a web browser. |
| [Open-SearchEngine](https://github.com/genXdev/GenXdev.Queries/tree/main#open-searchengine) | q | Opens a search query in the specified search engine using a web browser. |
| [Open-SimularWebSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-simularwebsiteinfo) | simularsite | Opens SimilarWeb website information for specified URLs in a web browser. |
| [Open-StackOverflowQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-stackoverflowquery) | qso | Opens Stack Overflow search queries in a web browser. |
| [Open-Timeline](https://github.com/genXdev/GenXdev.Queries/tree/main#open-timeline) | timeline | &nbsp; |
| [Open-ViralSimulation](https://github.com/genXdev/GenXdev.Queries/tree/main#open-viralsimulation) | viral | &nbsp; |
| [Open-WaybackMachineSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-waybackmachinesiteinfo) | wayback | Opens WaybackMachine site information in a web browser. |
| [Open-WebsiteAndPerformQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-websiteandperformquery) | owaq | Opens a webpage in a webbrowser and performs one or more queries. |
| [Open-WhoisHostSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-whoishostsiteinfo) | whois | Opens a Whois host information query in a web browser. |
| [Open-WikipediaNLQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-wikipedianlquery) | wikinl | Opens Dutch Wikipedia searches in a web browser. |
| [Open-WikipediaQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-wikipediaquery) | wiki | Opens a Wikipedia query in a webbrowser. |
| [Open-WolframAlphaQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-wolframalphaquery) | qalpha | Opens a Wolfram Alpha query in a web browser. |
| [Open-XGrokQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-xgrokquery) | aixg, askxgrok | Opens a X Grok query in a webbrowser |
| [Open-Yab](https://github.com/genXdev/GenXdev.Queries/tree/main#open-yab) | yab | Opens the YAB game in a web browser with configurable settings. |
| [Open-YabAIBattle](https://github.com/genXdev/GenXdev.Queries/tree/main#open-yabaibattle) | yabbattle | Opens the YabAI Battle game in a web browser. |
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
| [Invoke-WebbrowserTabPollingScript](https://github.com/genXdev/GenXdev.Queries/tree/main#invoke-webbrowsertabpollingscript) | &nbsp; | Executes a background polling script in a previously selected webbrowser tab. |
| [Open-AllGoogleLinks](https://github.com/genXdev/GenXdev.Queries/tree/main#open-allgooglelinks) | qlinks | Performs an infinite auto opening google search . |
| [Open-AllPossibleQueries](https://github.com/genXdev/GenXdev.Queries/tree/main#open-allpossiblequeries) | qq | Opens all possible query types for given search terms or URLs. |
| [Open-AllPossibleTextQueries](https://github.com/genXdev/GenXdev.Queries/tree/main#open-allpossibletextqueries) | qqq | Executes all Text query Cmdlets in parallel and displays results. |
| [Open-AllYoutubeVideos](https://github.com/genXdev/GenXdev.Queries/tree/main#open-allyoutubevideos) | qvideos, qyt | Opens and controls YouTube videos in a browser window with keyboard shortcuts. |
| [Open-BingCopilotQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-bingcopilotquery) | aibc | Opens a Bing CoPilot query in a webbrowser |
| [Open-BingQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-bingquery) | bq | Opens a Bing search query in a web browser. |
| [Open-BuiltWithSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-builtwithsiteinfo) | &nbsp; | Opens BuiltWith website queries in a web browser. |
| [Open-ChatGPTQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-chatgptquery) | aicgpt, askchatgpt | Opens a ChatGPT query in a web browser. |
| [Open-CloudLLMChat](https://github.com/genXdev/GenXdev.Queries/tree/main#open-cloudllmchat) | ask | Opens a cloud LLM chat interface for AI queries. |
| [Open-DeepSearchQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-deepsearchquery) | aideepseek, askdeepsearch | Opens a DeepSeek query in a webbrowser |
| [Open-GameOfLife](https://github.com/genXdev/GenXdev.Queries/tree/main#open-gameoflife) | conway, gameoflife | Opens Conway's Game of Life simulation in a web browser. |
| [Open-GenXdevAppCatalog](https://github.com/genXdev/GenXdev.Queries/tree/main#open-genxdevappcatalog) | appcatalog | Opens the GenXdev progressive webapps catalog in a web browser. |
| [Open-GithubCopilotQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-githubcopilotquery) | aigc, askghcopilot | Opens a Github CoPilot query in a webbrowser |
| [Open-GithubQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-githubquery) | qgh, qgithub | &nbsp; |
| [Open-GoogleGeminiQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-googlegeminiquery) | aigg, askgemini | Opens a Google Gemini query in a webbrowser |
| [Open-GoogleQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-googlequery) | &nbsp; | &nbsp; |
| [Open-GoogleSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-googlesiteinfo) | &nbsp; | Opens Google site information queries in a web browser. |
| [Open-IMDBQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-imdbquery) | imdb | Opens an IMDB search query in a web browser. |
| [Open-InstantStreetViewQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-instantstreetviewquery) | isv | Opens InstantStreetView queries in a web browser. |
| [Open-MovieQuote](https://github.com/genXdev/GenXdev.Queries/tree/main#open-moviequote) | moviequote | Opens a video of a movie quote in a web browser. |
| [Open-SearchEngine](https://github.com/genXdev/GenXdev.Queries/tree/main#open-searchengine) | q | Opens a search query in the specified search engine using a web browser. |
| [Open-SimularWebSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-simularwebsiteinfo) | simularsite | Opens SimilarWeb website information for specified URLs in a web browser. |
| [Open-StackOverflowQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-stackoverflowquery) | qso | Opens Stack Overflow search queries in a web browser. |
| [Open-Timeline](https://github.com/genXdev/GenXdev.Queries/tree/main#open-timeline) | timeline | &nbsp; |
| [Open-ViralSimulation](https://github.com/genXdev/GenXdev.Queries/tree/main#open-viralsimulation) | viral | &nbsp; |
| [Open-WaybackMachineSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-waybackmachinesiteinfo) | wayback | Opens WaybackMachine site information in a web browser. |
| [Open-WebsiteAndPerformQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-websiteandperformquery) | owaq | Opens a webpage in a webbrowser and performs one or more queries. |
| [Open-WhoisHostSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-whoishostsiteinfo) | whois | Opens a Whois host information query in a web browser. |
| [Open-WikipediaNLQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-wikipedianlquery) | wikinl | Opens Dutch Wikipedia searches in a web browser. |
| [Open-WikipediaQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-wikipediaquery) | wiki | Opens a Wikipedia query in a webbrowser. |
| [Open-WolframAlphaQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-wolframalphaquery) | qalpha | Opens a Wolfram Alpha query in a web browser. |
| [Open-XGrokQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-xgrokquery) | aixg, askxgrok | Opens a X Grok query in a webbrowser |
| [Open-Yab](https://github.com/genXdev/GenXdev.Queries/tree/main#open-yab) | yab | Opens the YAB game in a web browser with configurable settings. |
| [Open-YabAIBattle](https://github.com/genXdev/GenXdev.Queries/tree/main#open-yabaibattle) | yabbattle | Opens the YabAI Battle game in a web browser. |
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
| [Invoke-WebbrowserTabPollingScript](https://github.com/genXdev/GenXdev.Queries/tree/main#invoke-webbrowsertabpollingscript) | &nbsp; | Executes a background polling script in a previously selected webbrowser tab. |
| [Open-AllGoogleLinks](https://github.com/genXdev/GenXdev.Queries/tree/main#open-allgooglelinks) | qlinks | Performs an infinite auto opening google search . |
| [Open-AllPossibleQueries](https://github.com/genXdev/GenXdev.Queries/tree/main#open-allpossiblequeries) | qq | Opens all possible query types for given search terms or URLs. |
| [Open-AllPossibleTextQueries](https://github.com/genXdev/GenXdev.Queries/tree/main#open-allpossibletextqueries) | qqq | Executes all Text query Cmdlets in parallel and displays results. |
| [Open-AllYoutubeVideos](https://github.com/genXdev/GenXdev.Queries/tree/main#open-allyoutubevideos) | qvideos, qyt | Opens and controls YouTube videos in a browser window with keyboard shortcuts. |
| [Open-BingCopilotQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-bingcopilotquery) | aibc | Opens a Bing CoPilot query in a webbrowser |
| [Open-BingQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-bingquery) | bq | Opens a Bing search query in a web browser. |
| [Open-BuiltWithSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-builtwithsiteinfo) | &nbsp; | Opens BuiltWith website queries in a web browser. |
| [Open-ChatGPTQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-chatgptquery) | aicgpt, askchatgpt | Opens a ChatGPT query in a web browser. |
| [Open-CloudLLMChat](https://github.com/genXdev/GenXdev.Queries/tree/main#open-cloudllmchat) | ask | Opens a cloud LLM chat interface for AI queries. |
| [Open-DeepSearchQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-deepsearchquery) | aideepseek, askdeepsearch | Opens a DeepSeek query in a webbrowser |
| [Open-GameOfLife](https://github.com/genXdev/GenXdev.Queries/tree/main#open-gameoflife) | conway, gameoflife | Opens Conway's Game of Life simulation in a web browser. |
| [Open-GenXdevAppCatalog](https://github.com/genXdev/GenXdev.Queries/tree/main#open-genxdevappcatalog) | appcatalog | Opens the GenXdev progressive webapps catalog in a web browser. |
| [Open-GithubCopilotQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-githubcopilotquery) | aigc, askghcopilot | Opens a Github CoPilot query in a webbrowser |
| [Open-GithubQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-githubquery) | qgh, qgithub | &nbsp; |
| [Open-GoogleGeminiQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-googlegeminiquery) | aigg, askgemini | Opens a Google Gemini query in a webbrowser |
| [Open-GoogleQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-googlequery) | &nbsp; | &nbsp; |
| [Open-GoogleSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-googlesiteinfo) | &nbsp; | Opens Google site information queries in a web browser. |
| [Open-IMDBQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-imdbquery) | imdb | Opens an IMDB search query in a web browser. |
| [Open-InstantStreetViewQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-instantstreetviewquery) | isv | Opens InstantStreetView queries in a web browser. |
| [Open-MovieQuote](https://github.com/genXdev/GenXdev.Queries/tree/main#open-moviequote) | moviequote | Opens a video of a movie quote in a web browser. |
| [Open-SearchEngine](https://github.com/genXdev/GenXdev.Queries/tree/main#open-searchengine) | q | Opens a search query in the specified search engine using a web browser. |
| [Open-SimularWebSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-simularwebsiteinfo) | simularsite | Opens SimilarWeb website information for specified URLs in a web browser. |
| [Open-StackOverflowQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-stackoverflowquery) | qso | Opens Stack Overflow search queries in a web browser. |
| [Open-Timeline](https://github.com/genXdev/GenXdev.Queries/tree/main#open-timeline) | timeline | &nbsp; |
| [Open-ViralSimulation](https://github.com/genXdev/GenXdev.Queries/tree/main#open-viralsimulation) | viral | &nbsp; |
| [Open-WaybackMachineSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-waybackmachinesiteinfo) | wayback | Opens WaybackMachine site information in a web browser. |
| [Open-WebsiteAndPerformQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-websiteandperformquery) | owaq | Opens a webpage in a webbrowser and performs one or more queries. |
| [Open-WhoisHostSiteInfo](https://github.com/genXdev/GenXdev.Queries/tree/main#open-whoishostsiteinfo) | whois | Opens a Whois host information query in a web browser. |
| [Open-WikipediaNLQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-wikipedianlquery) | wikinl | Opens Dutch Wikipedia searches in a web browser. |
| [Open-WikipediaQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-wikipediaquery) | wiki | Opens a Wikipedia query in a webbrowser. |
| [Open-WolframAlphaQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-wolframalphaquery) | qalpha | Opens a Wolfram Alpha query in a web browser. |
| [Open-XGrokQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-xgrokquery) | aixg, askxgrok | Opens a X Grok query in a webbrowser |
| [Open-Yab](https://github.com/genXdev/GenXdev.Queries/tree/main#open-yab) | yab | Opens the YAB game in a web browser with configurable settings. |
| [Open-YabAIBattle](https://github.com/genXdev/GenXdev.Queries/tree/main#open-yabaibattle) | yabbattle | Opens the YabAI Battle game in a web browser. |
| [Open-YoutubeQuery](https://github.com/genXdev/GenXdev.Queries/tree/main#open-youtubequery) | youtube | Opens YouTube search queries in a web browser. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Queries/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Webbrowser

**A Windows PowerShell module for webbrowser operations**

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [Approve-FirefoxDebugging](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#approve-firefoxdebugging) | &nbsp; | Configures Firefox's debugging and standalone app mode features. |
| [Clear-WebbrowserTabSiteApplicationData](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#clear-webbrowsertabsiteapplicationdata) | clearsitedata | Clears all browser storage data for the current tab in Edge or Chrome. |
| [Close-Webbrowser](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#close-webbrowser) | wbc | Closes one or more webbrowser instances selectively. |
| [Close-WebbrowserTab](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#close-webbrowsertab) | CloseTab, ct | Closes the currently selected webbrowser tab. |
| [Connect-PlaywrightViaDebuggingPort](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#connect-playwrightviadebuggingport) | &nbsp; | Connects to an existing browser instance via debugging port. |
| [Export-BrowserBookmarks](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#export-browserbookmarks) | &nbsp; | Exports browser bookmarks to a JSON file. |
| [Find-BrowserBookmark](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#find-browserbookmark) | bookmarks | Finds bookmarks from one or more web browsers. |
| [Get-BrowserBookmark](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#get-browserbookmark) | gbm | Returns all bookmarks from installed web browsers. |
| [Get-ChromeRemoteDebuggingPort](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#get-chromeremotedebuggingport) | &nbsp; | Returns the configured remote debugging port for Google Chrome. |
| [Get-ChromiumRemoteDebuggingPort](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#get-chromiumremotedebuggingport) | &nbsp; | Returns the remote debugging port for the system's default Chromium browser. |
| [Get-ChromiumSessionReference](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#get-chromiumsessionreference) | &nbsp; | Gets a serializable reference to the current browser tab session. |
| [Get-DefaultWebbrowser](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#get-defaultwebbrowser) | &nbsp; | Returns the configured default web browser for the current user. |
| [Get-EdgeRemoteDebuggingPort](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#get-edgeremotedebuggingport) | &nbsp; | Returns the configured remote debugging port for Microsoft Edge browser. |
| [Get-PlaywrightProfileDirectory](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#get-playwrightprofiledirectory) | &nbsp; | Gets the Playwright browser profile directory for persistent sessions. |
| [Get-Webbrowser](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#get-webbrowser) | &nbsp; | Returns a collection of installed modern web browsers. |
| [Get-WebbrowserTabDomNodes](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#get-webbrowsertabdomnodes) | wl | Queries and manipulates DOM nodes in the active browser tab using CSS selectors. |
| [Import-BrowserBookmarks](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#import-browserbookmarks) | &nbsp; | Imports bookmarks from a file or collection into a web browser. |
| [Import-GenXdevBookmarkletMenu](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#import-genxdevbookmarkletmenu) | &nbsp; | Imports GenXdev JavaScript bookmarklets into browser bookmark collections. |
| [Invoke-WebbrowserEvaluation](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#invoke-webbrowserevaluation) | et, Eval | Executes JavaScript code in a selected web browser tab. |
| [Open-BrowserBookmarks](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#open-browserbookmarks) | sites | Opens browser bookmarks that match specified search criteria. |
| [Open-Webbrowser](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#open-webbrowser) | wb | Opens URLs in one or more browser windows with optional positioning and styling. |
| [Open-WebbrowserSideBySide](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#open-webbrowsersidebyside) | wbn | Launches a new web browser window with specific positioning. |
| [Resume-WebbrowserTabVideo](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#resume-webbrowsertabvideo) | wbvideoplay | Resumes video playback in a YouTube browser tab. |
| [Select-WebbrowserTab](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#select-webbrowsertab) | st | Selects a browser tab for automation in Chrome or Edge. |
| [Set-BrowserVideoFullscreen](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#set-browservideofullscreen) | fsvideo | Maximizes the first video element found in the current browser tab. |
| [Set-RemoteDebuggerPortInBrowserShortcuts](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#set-remotedebuggerportinbrowsershortcuts) | &nbsp; | Updates browser shortcuts to enable remote debugging ports. |
| [Set-WebbrowserTabLocation](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#set-webbrowsertablocation) | lt, Nav | Navigates the current webbrowser tab to a specified URL. |
| [Show-WebsiteInAllBrowsers](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#show-websiteinallbrowsers) | &nbsp; | Opens a URL in multiple browsers simultaneously in a mosaic layout. |
| [Stop-WebbrowserVideos](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#stop-webbrowservideos) | ssst, wbsst, wbvideostop | Pauses video playback in all active browser sessions. |
| [Unprotect-WebbrowserTab](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#unprotect-webbrowsertab) | wbctrl | Takes control of a selected web browser tab for interactive manipulation. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Webbrowser.Playwright

**A Windows PowerShell module for webbrowser.playwright operations**

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [Approve-FirefoxDebugging](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#approve-firefoxdebugging) | &nbsp; | Configures Firefox's debugging and standalone app mode features. |
| [Clear-WebbrowserTabSiteApplicationData](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#clear-webbrowsertabsiteapplicationdata) | clearsitedata | Clears all browser storage data for the current tab in Edge or Chrome. |
| [Close-Webbrowser](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#close-webbrowser) | wbc | Closes one or more webbrowser instances selectively. |
| [Close-WebbrowserTab](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#close-webbrowsertab) | CloseTab, ct | Closes the currently selected webbrowser tab. |
| [Connect-PlaywrightViaDebuggingPort](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#connect-playwrightviadebuggingport) | &nbsp; | Connects to an existing browser instance via debugging port. |
| [Export-BrowserBookmarks](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#export-browserbookmarks) | &nbsp; | Exports browser bookmarks to a JSON file. |
| [Find-BrowserBookmark](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#find-browserbookmark) | bookmarks | Finds bookmarks from one or more web browsers. |
| [Get-BrowserBookmark](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#get-browserbookmark) | gbm | Returns all bookmarks from installed web browsers. |
| [Get-ChromeRemoteDebuggingPort](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#get-chromeremotedebuggingport) | &nbsp; | Returns the configured remote debugging port for Google Chrome. |
| [Get-ChromiumRemoteDebuggingPort](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#get-chromiumremotedebuggingport) | &nbsp; | Returns the remote debugging port for the system's default Chromium browser. |
| [Get-ChromiumSessionReference](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#get-chromiumsessionreference) | &nbsp; | Gets a serializable reference to the current browser tab session. |
| [Get-DefaultWebbrowser](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#get-defaultwebbrowser) | &nbsp; | Returns the configured default web browser for the current user. |
| [Get-EdgeRemoteDebuggingPort](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#get-edgeremotedebuggingport) | &nbsp; | Returns the configured remote debugging port for Microsoft Edge browser. |
| [Get-PlaywrightProfileDirectory](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#get-playwrightprofiledirectory) | &nbsp; | Gets the Playwright browser profile directory for persistent sessions. |
| [Get-Webbrowser](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#get-webbrowser) | &nbsp; | Returns a collection of installed modern web browsers. |
| [Get-WebbrowserTabDomNodes](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#get-webbrowsertabdomnodes) | wl | Queries and manipulates DOM nodes in the active browser tab using CSS selectors. |
| [Import-BrowserBookmarks](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#import-browserbookmarks) | &nbsp; | Imports bookmarks from a file or collection into a web browser. |
| [Import-GenXdevBookmarkletMenu](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#import-genxdevbookmarkletmenu) | &nbsp; | Imports GenXdev JavaScript bookmarklets into browser bookmark collections. |
| [Invoke-WebbrowserEvaluation](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#invoke-webbrowserevaluation) | et, Eval | Executes JavaScript code in a selected web browser tab. |
| [Open-BrowserBookmarks](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#open-browserbookmarks) | sites | Opens browser bookmarks that match specified search criteria. |
| [Open-Webbrowser](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#open-webbrowser) | wb | Opens URLs in one or more browser windows with optional positioning and styling. |
| [Open-WebbrowserSideBySide](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#open-webbrowsersidebyside) | wbn | Launches a new web browser window with specific positioning. |
| [Resume-WebbrowserTabVideo](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#resume-webbrowsertabvideo) | wbvideoplay | Resumes video playback in a YouTube browser tab. |
| [Select-WebbrowserTab](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#select-webbrowsertab) | st | Selects a browser tab for automation in Chrome or Edge. |
| [Set-BrowserVideoFullscreen](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#set-browservideofullscreen) | fsvideo | Maximizes the first video element found in the current browser tab. |
| [Set-RemoteDebuggerPortInBrowserShortcuts](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#set-remotedebuggerportinbrowsershortcuts) | &nbsp; | Updates browser shortcuts to enable remote debugging ports. |
| [Set-WebbrowserTabLocation](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#set-webbrowsertablocation) | lt, Nav | Navigates the current webbrowser tab to a specified URL. |
| [Show-WebsiteInAllBrowsers](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#show-websiteinallbrowsers) | &nbsp; | Opens a URL in multiple browsers simultaneously in a mosaic layout. |
| [Stop-WebbrowserVideos](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#stop-webbrowservideos) | ssst, wbsst, wbvideostop | Pauses video playback in all active browser sessions. |
| [Unprotect-WebbrowserTab](https://github.com/genXdev/GenXdev.Webbrowser/tree/main#unprotect-webbrowsertab) | wbctrl | Takes control of a selected web browser tab for interactive manipulation. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Webbrowser/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Windows

**A Windows PowerShell module for windows operations**

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [Add-WireGuardPeer](https://github.com/genXdev/GenXdev.Windows/tree/main#add-wireguardpeer) | &nbsp; | Adds a new WireGuard VPN peer (client) configuration to the server. |
| [CurrentUserHasElevatedRights](https://github.com/genXdev/GenXdev.Windows/tree/main#currentuserhaselevatedrights) | &nbsp; | Checks if the current user has elevated rights. |
| [EnsureDockerDesktop](https://github.com/genXdev/GenXdev.Windows/tree/main#ensuredockerdesktop) | &nbsp; | Checks if the WinGet PowerShell module is installed. |
| [EnsurePSTools](https://github.com/genXdev/GenXdev.Windows/tree/main#ensurepstools) | &nbsp; | Ensures Sysinternals tools (PSTools) are installed and available. |
| [EnsureWireGuard](https://github.com/genXdev/GenXdev.Windows/tree/main#ensurewireguard) | &nbsp; | Ensures WireGuard VPN service is installed and running via Docker container. |
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
| [Get-Window](https://github.com/genXdev/GenXdev.Windows/tree/main#get-window) | gwin, window | Gets window information for specified processes or window handles. |
| [Get-WireGuardPeerQRCode](https://github.com/genXdev/GenXdev.Windows/tree/main#get-wireguardpeerqrcode) | &nbsp; | Generates a QR code for a WireGuard VPN peer configuration. |
| [Get-WireGuardPeers](https://github.com/genXdev/GenXdev.Windows/tree/main#get-wireguardpeers) | &nbsp; | Gets information about all WireGuard VPN peers configured on the system. |
| [Get-WireGuardStatus](https://github.com/genXdev/GenXdev.Windows/tree/main#get-wireguardstatus) | &nbsp; | Gets detailed status information about the WireGuard VPN server. |
| [Initialize-ScheduledTaskScripts](https://github.com/genXdev/GenXdev.Windows/tree/main#initialize-scheduledtaskscripts) | &nbsp; | Creates scheduled tasks that run PowerShell scripts at specified intervals. |
| [Invoke-WindowsUpdate](https://github.com/genXdev/GenXdev.Windows/tree/main#invoke-windowsupdate) | updatewindows | Checks if Windows is up to date and optionally installs available updates. |
| [Pop-Window](https://github.com/genXdev/GenXdev.Windows/tree/main#pop-window) | popw | Pops the last active window helper from the stack with optional modifications. |
| [Push-Window](https://github.com/genXdev/GenXdev.Windows/tree/main#push-window) | pushw | Pushes the current window onto the window stack with optional modifications. |
| [Remove-WireGuardPeer](https://github.com/genXdev/GenXdev.Windows/tree/main#remove-wireguardpeer) | &nbsp; | Removes a WireGuard VPN peer configuration. |
| [Reset-WireGuardConfiguration](https://github.com/genXdev/GenXdev.Windows/tree/main#reset-wireguardconfiguration) | &nbsp; | Resets the WireGuard VPN server configuration, removing all peers. |
| [Send-Key](https://github.com/genXdev/GenXdev.Windows/tree/main#send-key) | invokekeys, sendkeys | Sends simulated keystrokes to a window or process. |
| [Set-ClipboardFiles](https://github.com/genXdev/GenXdev.Windows/tree/main#set-clipboardfiles) | setclipfiles | Sets files to the Windows clipboard for file operations like copy/paste. |
| [Set-ForegroundWindow](https://github.com/genXdev/GenXdev.Windows/tree/main#set-foregroundwindow) | &nbsp; | Brings the specified window to the foreground and makes it the active window. |
| [Set-KnownFolderPath](https://github.com/genXdev/GenXdev.Windows/tree/main#set-knownfolderpath) | &nbsp; | Modifies the physical path of a Windows known folder. |
| [Set-TaskbarAlignment](https://github.com/genXdev/GenXdev.Windows/tree/main#set-taskbaralignment) | &nbsp; | Configures Windows 11+ taskbar alignment between center and left positions. |
| [Set-WindowPosition](https://github.com/genXdev/GenXdev.Windows/tree/main#set-windowposition) | wp | Positions and resizes windows when explicit positioning parameters are provided. |
| [Set-WindowPositionForSecondary](https://github.com/genXdev/GenXdev.Windows/tree/main#set-windowpositionforsecondary) | wps | Positions a window on the secondary monitor with specified layout options. |
| [Set-WindowsWallpaper](https://github.com/genXdev/GenXdev.Windows/tree/main#set-windowswallpaper) | setaswallpaper | Sets a random wallpaper from a specified directory. |
| [Start-ProcessWithPriority](https://github.com/genXdev/GenXdev.Windows/tree/main#start-processwithpriority) | nice | Starts a process with a specified priority level. |
| [Test-PathUsingWindowsDefender](https://github.com/genXdev/GenXdev.Windows/tree/main#test-pathusingwindowsdefender) | HasNoVirus, virusscan | Scans files or directories for malware using Windows Defender. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

## GenXdev.Windows.WireGuard

**A Windows PowerShell module for windows.wireguard operations**

# Cmdlet Index

| Command | Aliases | Description |
| :--- | :--- | :--- |
| [Add-WireGuardPeer](https://github.com/genXdev/GenXdev.Windows/tree/main#add-wireguardpeer) | &nbsp; | Adds a new WireGuard VPN peer (client) configuration to the server. |
| [CurrentUserHasElevatedRights](https://github.com/genXdev/GenXdev.Windows/tree/main#currentuserhaselevatedrights) | &nbsp; | Checks if the current user has elevated rights. |
| [EnsureDockerDesktop](https://github.com/genXdev/GenXdev.Windows/tree/main#ensuredockerdesktop) | &nbsp; | Checks if the WinGet PowerShell module is installed. |
| [EnsurePSTools](https://github.com/genXdev/GenXdev.Windows/tree/main#ensurepstools) | &nbsp; | Ensures Sysinternals tools (PSTools) are installed and available. |
| [EnsureWireGuard](https://github.com/genXdev/GenXdev.Windows/tree/main#ensurewireguard) | &nbsp; | Ensures WireGuard VPN service is installed and running via Docker container. |
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
| [Get-Window](https://github.com/genXdev/GenXdev.Windows/tree/main#get-window) | gwin, window | Gets window information for specified processes or window handles. |
| [Get-WireGuardPeerQRCode](https://github.com/genXdev/GenXdev.Windows/tree/main#get-wireguardpeerqrcode) | &nbsp; | Generates a QR code for a WireGuard VPN peer configuration. |
| [Get-WireGuardPeers](https://github.com/genXdev/GenXdev.Windows/tree/main#get-wireguardpeers) | &nbsp; | Gets information about all WireGuard VPN peers configured on the system. |
| [Get-WireGuardStatus](https://github.com/genXdev/GenXdev.Windows/tree/main#get-wireguardstatus) | &nbsp; | Gets detailed status information about the WireGuard VPN server. |
| [Initialize-ScheduledTaskScripts](https://github.com/genXdev/GenXdev.Windows/tree/main#initialize-scheduledtaskscripts) | &nbsp; | Creates scheduled tasks that run PowerShell scripts at specified intervals. |
| [Invoke-WindowsUpdate](https://github.com/genXdev/GenXdev.Windows/tree/main#invoke-windowsupdate) | updatewindows | Checks if Windows is up to date and optionally installs available updates. |
| [Pop-Window](https://github.com/genXdev/GenXdev.Windows/tree/main#pop-window) | popw | Pops the last active window helper from the stack with optional modifications. |
| [Push-Window](https://github.com/genXdev/GenXdev.Windows/tree/main#push-window) | pushw | Pushes the current window onto the window stack with optional modifications. |
| [Remove-WireGuardPeer](https://github.com/genXdev/GenXdev.Windows/tree/main#remove-wireguardpeer) | &nbsp; | Removes a WireGuard VPN peer configuration. |
| [Reset-WireGuardConfiguration](https://github.com/genXdev/GenXdev.Windows/tree/main#reset-wireguardconfiguration) | &nbsp; | Resets the WireGuard VPN server configuration, removing all peers. |
| [Send-Key](https://github.com/genXdev/GenXdev.Windows/tree/main#send-key) | invokekeys, sendkeys | Sends simulated keystrokes to a window or process. |
| [Set-ClipboardFiles](https://github.com/genXdev/GenXdev.Windows/tree/main#set-clipboardfiles) | setclipfiles | Sets files to the Windows clipboard for file operations like copy/paste. |
| [Set-ForegroundWindow](https://github.com/genXdev/GenXdev.Windows/tree/main#set-foregroundwindow) | &nbsp; | Brings the specified window to the foreground and makes it the active window. |
| [Set-KnownFolderPath](https://github.com/genXdev/GenXdev.Windows/tree/main#set-knownfolderpath) | &nbsp; | Modifies the physical path of a Windows known folder. |
| [Set-TaskbarAlignment](https://github.com/genXdev/GenXdev.Windows/tree/main#set-taskbaralignment) | &nbsp; | Configures Windows 11+ taskbar alignment between center and left positions. |
| [Set-WindowPosition](https://github.com/genXdev/GenXdev.Windows/tree/main#set-windowposition) | wp | Positions and resizes windows when explicit positioning parameters are provided. |
| [Set-WindowPositionForSecondary](https://github.com/genXdev/GenXdev.Windows/tree/main#set-windowpositionforsecondary) | wps | Positions a window on the secondary monitor with specified layout options. |
| [Set-WindowsWallpaper](https://github.com/genXdev/GenXdev.Windows/tree/main#set-windowswallpaper) | setaswallpaper | Sets a random wallpaper from a specified directory. |
| [Start-ProcessWithPriority](https://github.com/genXdev/GenXdev.Windows/tree/main#start-processwithpriority) | nice | Starts a process with a specified priority level. |
| [Test-PathUsingWindowsDefender](https://github.com/genXdev/GenXdev.Windows/tree/main#test-pathusingwindowsdefender) | HasNoVirus, virusscan | Scans files or directories for malware using Windows Defender. |

📖 [Full Documentation](https://github.com/genXdev/GenXdev.Windows/blob/main/README.md) | ↑ [Back to Module Overview](#module-overview)

<br/><hr/><br/>

