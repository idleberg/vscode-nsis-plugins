# vscode-nsis-plugins

[![Version](https://img.shields.io/github/v/release/idleberg/vscode-nsis-plugins?style=for-the-badge)](https://github.com/idleberg/vscode-nsis-plugins/releases)
[![Visual Studio Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/idleberg.nsis-plugins?style=for-the-badge&label=Marketplace)](https://marketplace.visualstudio.com/items?itemName=idleberg.nsis-plugins)
[![Open VSX Downloads](https://img.shields.io/open-vsx/dt/idleberg/nsis-plugins?style=for-the-badge&label=Open%20VSX)](https://open-vsx.org/extension/idleberg/nsis-plugins)
[![Build](https://img.shields.io/github/actions/workflow/status/idleberg/vscode-nsis-plugins/default.yml?style=for-the-badge)](https://github.com/idleberg/vscode-nsis-plugins/actions)

IntelliSense for third-party plug-ins for Nullsoft Scriptable Install System (NSIS)

## Installation

Visual Studio Code 1.7 (and higher) will automatically install the [NSIS extension](https://github.com/idleberg/vscode-nsis) as dependency. If you're using an older version, you will have to do so yourself.

### Extension Marketplace

Launch Quick Open, paste the following command, and press <kbd>Enter</kbd>

`ext install idleberg.nsis-plugins`

### CLI

With [shell commands](https://code.visualstudio.com/docs/editor/command-line) installed, you can use the following command to install the extension:

`$ code --install-extension idleberg.nsis-plugins`

### Packaged Extension

Download the packaged extension from the the [release page](https://github.com/idleberg/vscode-nsis-plugins/releases) and install it from the command-line:

```bash
$ code --install-extension path/to/nsis-plugins-*.vsix
```

Alternatively, you can download the packaged extension from the [Open VSX Registry](https://open-vsx.org/) or install it using the [`ovsx`](https://www.npmjs.com/package/ovsx) command-line tool:

```bash
$ ovsx get idleberg.nsis-plugins
```

### Clone Repository

Change to your Visual Studio Code extensions directory:

```powershell
# Windows Powershell
cd $Env:USERPROFILES\.vscode\extensions

# Windows Command Prompt
$ cd %USERPROFILE%\.vscode\extensions
```

```bash
# Linux & macOS
$ cd ~/.vscode/extensions/
```

Clone repository as `nsis-plugins`:

```bash
$ git clone https://github.com/idleberg/vscode-nsis-plugins nsis-plugins
```

## Supported plug-ins

- [AccessControl](http://nsis.sourceforge.net/AccessControl_plug-in)
- [Aero](http://nsis.sourceforge.net/Aero_plug-in)
- [Animate](http://nsis.sourceforge.net/Animate_plug-in)
- [AnimGif](http://nsis.sourceforge.net/AnimGif_plug-in)
- [AppAssocReg](http://nsis.sourceforge.net/Application_Association_Registration_plug-in)
- [ApplicationID](http://nsis.sourceforge.net/ApplicationID_plug-in)
- [Base64](http://nsis.sourceforge.net/Base64)
- [BaseConvert](http://nsis.sourceforge.net/BaseConvert_plug-in)
- [BDEAlias](http://nsis.sourceforge.net/BDEAlias_plug-in)
- [BgWorker](http://nsis.sourceforge.net/BgWorker_plug-in)
- [Blowfish++](http://nsis.sourceforge.net/Blowfish%2B%2B_plug-in)
- [Blowfish](http://nsis.sourceforge.net/Blowfish_plug-in)
- [BrandingURL](http://nsis.sourceforge.net/BrandingURL_plug-in)
- [ButtonEvent](http://nsis.sourceforge.net/ButtonEvent_plug-in)
- [CabDLL](http://nsis.sourceforge.net/CabDLL_plug-in)
- [CABSetup](http://nsis.sourceforge.net/CABSetup_plug-in)
- [CallAnsiPlugin](http://nsis.sourceforge.net/CallAnsiPlugin_plug-in)
- [CDRom](http://nsis.sourceforge.net/CDRom_plug-in)
- [ChangeRes](http://nsis.sourceforge.net/ChangeRes_plug-in)
- [CharToAscii](http://nsis.sourceforge.net/CharToASCII)
- [CLR](http://nsis.sourceforge.net/Call_.NET_DLL_methods_plug-in)
- [ComPlusAdmin](http://nsis.sourceforge.net/ComPlusAdmin_plug-in)
- [CPUDesc](http://nsis.sourceforge.net/CPUDesc_plug-in)
- [CPUFeatures](http://nsis.sourceforge.net/CPUFeatures_plug-in)
- [CreateMutex](http://nsis.sourceforge.net/CreateMutex_plug-in)
- [CRCCheck](http://nsis.sourceforge.net/CRCCheck_plug-in)
- [Crypto](http://nsis.sourceforge.net/Crypto_plug-in)
- [CustomLicense](http://nsis.sourceforge.net/CustomLicense_plug-in)
- [DcryptDll](http://nsis.sourceforge.net/DcryptDll_plug-in)
- [Dialogs](http://nsis.sourceforge.net/Dialogs_plug-in)
- [DlgHost](http://nsis.sourceforge.net/DlgHost_plug-in)
- [DotNetChecker](https://github.com/ProjectHuman/NsisDotNetChecker)
- [DumpLog](http://nsis.sourceforge.net/DumpLog_plug-in)
- [DumpState](http://nsis.sourceforge.net/DumpState_plug-in)
- [EBanner](http://nsis.sourceforge.net/EBanner_plug-in)
- [Email](http://nsis.sourceforge.net/Email_validation_plug-in)
- [EmbeddedLists](http://nsis.sourceforge.net/EmbeddedLists_plug-in)
- [EnumCDs](http://nsis.sourceforge.net/EnumCDs_plug-in)
- [EnumINI](http://nsis.sourceforge.net/EnumINI_plug-in)
- [EnVar](http://nsis.sourceforge.net/EnVar_plug-in)
- [EventLog](http://nsis.sourceforge.net/EventLog_plug-in)
- [ExDlg](http://nsis.sourceforge.net/ExDlg_plug-in)
- [ExecCmd](http://nsis.sourceforge.net/ExecCmd_plug-in)
- [ExecDos](http://nsis.sourceforge.net/ExecDos_plug-in)
- [ExecPri](http://nsis.sourceforge.net/ExecPri_plug-in)
- [ExecTimeout](http://nsis.sourceforge.net/ExecTimeout_plug-in)
- [ExLicensePage](http://nsis.sourceforge.net/ExLicensePage_plug-in)
- [ExtractDllEx](http://nsis.sourceforge.net/ExtractDLLEx_plug-in)
- [FindProcDLL](http://nsis.sourceforge.net/FindProcDLL_plug-in)
- [Firewall-Disabler](http://nsis.sourceforge.net/Firewall-Disabler_plug-in)
- [FloatOP](http://nsis.sourceforge.net/FloatOP_plug-in)
- [FontName](http://nsis.sourceforge.net/FontName_plug-in)
- [FreeArc](http://nsis.sourceforge.net/FreeArc_plug-in)
- [Games](http://nsis.sourceforge.net/Games_plug-in)
- [GetFirstRemovableDrive](http://nsis.sourceforge.net/GetFirstRemovableDrive_plug-in)
- [GetVersion](<http://nsis.sourceforge.net/GetVersion_(Windows)_plug-in>)
- [HandleFileDragDrop](http://nsis.sourceforge.net/HandleFileDragDrop_plug-in)
- [HelpButton](http://nsis.sourceforge.net/HelpButton_plug-in)
- [HwInfo](http://nsis.sourceforge.net/HwInfo_plug-in)
- [IEFunctions](http://nsis.sourceforge.net/IEFunctions_plug-in)
- [InetBgDL](http://nsis.sourceforge.net/InetBgDL_plug-in)
- [Inetc](http://nsis.sourceforge.net/Inetc_plug-in)
- [InetLoad](http://nsis.sourceforge.net/InetLoad_plug-in)
- [InstDrv](http://nsis.sourceforge.net/InstDrv_plug-in)
- [Internet](http://nsis.sourceforge.net/Internet_plug-in)
- [InvokeShellVerb](http://nsis.sourceforge.net/Invoke_Shell_Verb_plugin)
- [IP](http://nsis.sourceforge.net/IP_plug-in)
- [IpConfig](http://nsis.sourceforge.net/IpConfig_plugin)
- [KillProc](http://nsis.sourceforge.net/KillProc_plug-in)
- [KillProcDLL](http://nsis.sourceforge.net/KillProcDLL_plug-in)
- [Linker](http://nsis.sourceforge.net/Linker_plug-in)
- [LiteFirewall](http://nsis.sourceforge.net/LiteFirewall_Plugin)
- [Locate](http://nsis.sourceforge.net/Locate_plugin)
- [LockedList](http://nsis.sourceforge.net/LockedList_plug-in)
- [LogEx](http://nsis.sourceforge.net/LogEx_plug-in)
- [Marquee](http://nsis.sourceforge.net/Marquee_plug-in)
- [MD5](http://nsis.sourceforge.net/MD5_plugin)
- [Metadl](http://nsis.sourceforge.net/Metadl)
- [MoreInfo](http://nsis.sourceforge.net/MoreInfo_plug-in)
- [MSIBanner](http://nsis.sourceforge.net/MSIBanner_plug-in)
- [MSSQL OLEDB](http://nsis.sourceforge.net/MSSQL_OLEDB_plug-in)
- [name2ip](http://nsis.sourceforge.net/Name2ip_plugin)
- [NewAdvSplash](http://nsis.sourceforge.net/NewAdvSplash_plug-in)
- [NotifyIcon](http://nsis.sourceforge.net/NotifyIcon_plug-in)
- [nsArray](http://nsis.sourceforge.net/Arrays_in_NSIS)
- [NsExpr](http://nsis.sourceforge.net/NsExpr_plug-in)
- [NsFlash](http://forums.winamp.com/showthread.php?t=374506)
- [Nsis7z](http://nsis.sourceforge.net/Nsis7z_plug-in)
- [NSIS_SkinCrafter](http://nsis.sourceforge.net/NSIS_SkinCrafter_Plugin_plug-in)
- [NsisCrypt](http://nsis.sourceforge.net/NsisCrypt_plug-in)
- [NsisDDE](http://nsis.sourceforge.net/NsisDDE_plug-in)
- [NSISDirEx](http://nsis.sourceforge.net/NSISDirEx_plug-in)
- [nsisdt](http://nsis.sourceforge.net/NSIS-Date_plug-in)
- [nsisFile](http://nsis.sourceforge.net/NsisFile_plug-in)
- [NsisFirewall](http://nsis.sourceforge.net/NsisFirewall_plug-in)
- [NsisIIS](http://nsis.sourceforge.net/NsisIIS_plug-in)
- [NSISList](http://nsis.sourceforge.net/NSISList_plug-in)
- [NSISLog](http://nsis.sourceforge.net/NSISLog_plug-in)
- [nsisMultiMon](http://nsis.sourceforge.net/NSISMultiMon_plug-in)
- [nsisos](http://nsis.sourceforge.net/NSIS-OS_plug-in)
- [NSISpcre](http://nsis.sourceforge.net/NSISpcre_plug-in)
- [NsisSlideshow](http://nsis.sourceforge.net/NsisSlideshow_plug-in)
- [nsisStartMenu](http://nsis.sourceforge.net/NsisStartMenu_plug-in)
- [nsisunz](http://nsis.sourceforge.net/Nsisunz_plug-in)
- [NsisUrlLib](http://nsis.sourceforge.net/NsisUrlLib_plug-in)
- [nsisXML (by Wizou)](<http://nsis.sourceforge.net/NsisXML_plug-in_(by_Wizou)>)
- [nsJSON](http://nsis.sourceforge.net/NsJSON_plug-in)
- [nsKeyHook](http://nsis.sourceforge.net/NsKeyHook_plug-in)
- [NsMCI](http://nsis.sourceforge.net/NsMCI_plug-in)
- [NsODBC](http://nsis.sourceforge.net/NsODBC_plug-in)
- [nsProcess](http://nsis.sourceforge.net/NsProcess_plugin)
- [nsPython](http://nsis.sourceforge.net/NsPython_plug-in)
- [NsRandom](http://nsis.sourceforge.net/NsRandom_plug-in)
- [NsResize](http://nsis.sourceforge.net/NsResize_plug-in)
- [NsRestartExplorer](http://nsis.sourceforge.net/NsRestartExplorer_plug-in)
- [NsRichEdit](http://nsis.sourceforge.net/NsRichEdit_plug-in)
- [nsSCM](http://nsis.sourceforge.net/NsSCM_plug-in)
- [nsScreenshot](http://nsis.sourceforge.net/NsScreenshot_plug-in)
- [nsThread](http://nsis.sourceforge.net/NsThread_plug-in)
- [nsUnzip](http://nsis.sourceforge.net/NsUnzip_plugin)
- [nsVersionInfo](http://nsis.sourceforge.net/NsVersionInfo_plugin)
- [nsWeb](http://nsis.sourceforge.net/NsWeb_plug-in)
- [nsXML](<http://nsis.sourceforge.net/NsXML_plug-in_(by_rsegal)>)
- [Nwiz](http://nsis.sourceforge.net/Nwiz_plug-in)
- [PassDialog](http://nsis.sourceforge.net/PassDialog_plug-in)
- [Perl](http://nsis.sourceforge.net/Perl_plugin)
- [PixelShader](http://nsis.sourceforge.net/PixelShaderCheck)
- [PowerShell](http://nsis.sourceforge.net/Execute_PowerShell_script_or_command)
- [Processes](http://nsis.sourceforge.net/Processes_plug-in)
- [ProxySettings](http://nsis.sourceforge.net/ProxySettings)
- [Pwgen](http://nsis.sourceforge.net/Pwgen_plug-in)
- [RegBin](http://nsis.sourceforge.net/RegBin_plug-in)
- [Registry](http://nsis.sourceforge.net/Registry_plug-in)
- [SAFER](http://nsis.sourceforge.net/SAFER_plug-in)
- [ScrollLicense](http://nsis.sourceforge.net/ScrollLicense_plug-in)
- [SelfDel](http://nsis.sourceforge.net/SelfDel_plug-in)
- [Services](http://nsis.sourceforge.net/Services_plug-in)
- [SFhelper](http://nsis.sourceforge.net/SFhelper_Plugin)
- [ShellExecAsUser](http://nsis.sourceforge.net/ShellExecAsUser_plug-in)
- [ShellLink](http://nsis.sourceforge.net/ShellLink_plug-in)
- [ShutDown](http://nsis.sourceforge.net/ShutDown_plug-in)
- [ShutdownAllow](http://nsis.sourceforge.net/ShutdownAllow_plug-in)
- [SimpleBg](http://nsis.sourceforge.net/SimpleBg_plug-in)
- [SimpleFC](http://nsis.sourceforge.net/NSIS_Simple_Firewall_Plugin)
- [SimpleSC](http://nsis.sourceforge.net/NSIS_Simple_Service_Plugin)
- [SkinnedButton](http://nsis.sourceforge.net/SkinnedButton_plug-in)
- [SkinnedControls](http://nsis.sourceforge.net/SkinnedControls_plug-in)
- [SpiderBanner](http://nsis.sourceforge.net/SpiderBanner_plug-in)
- [Stack](http://nsis.sourceforge.net/Stack_plug-in)
- [StdUtils](http://nsis.sourceforge.net/StdUtils_plug-in)
- [SysRestore](http://nsis.sourceforge.net/SysRestore_plug-in)
- [TAPIhelp](http://nsis.sourceforge.net/TAPIhelp_plug-in)
- [TCP](http://nsis.sourceforge.net/TCP_plug-in)
- [TextReplace](http://nsis.sourceforge.net/TextReplace_plugin)
- [ThreadTimer](http://nsis.sourceforge.net/ThreadTimer_plug-in)
- [Time](http://nsis.sourceforge.net/Time_plug-in)
- [TitlebarProgress](http://nsis.sourceforge.net/Time_plug-in)
- [ToggleInstFiles](http://nsis.sourceforge.net/ToggleInstFiles_plug-in)
- [ToolTips](http://nsis.sourceforge.net/ToolTips_plug-in)
- [UAC](http://nsis.sourceforge.net/UAC_plug-in)
- [UltraModernUI](http://nsis.sourceforge.net/UltraModernUI)
- [Unicode](http://nsis.sourceforge.net/Unicode_plug-in)
- [UnicodePathTest](http://nsis.sourceforge.net/UnicodePathTest_plug-in)
- [UnTGZ](http://nsis.sourceforge.net/UnTGZ_plug-in)
- [UserMgr](http://nsis.sourceforge.net/UserMgr_plug-in)
- [Version](http://nsis.sourceforge.net/Version_plug-in)
- [w7tbp](http://nsis.sourceforge.net/TaskbarProgress_plug-in)
- [WinShell](http://nsis.sourceforge.net/WinShell_plug-in)
- [WimImage](http://forums.winamp.com/showthread.php?t=377498)
- [WmiInspector](http://nsis.sourceforge.net/WmiInspector_plug-in)
- [XiMoL](http://nsis.sourceforge.net/XiMoL_plug-in)
- [XML](http://nsis.sourceforge.net/XML_plug-in)
- [xtInfoPlugin](http://nsis.sourceforge.net/XtInfoPlugin_plug-in)
- [ZipDLL](http://nsis.sourceforge.net/ZipDLL_plug-in)

## Related

- [vscode-nsis](https://marketplace.visualstudio.com/items?itemName=idleberg.nsis) - NSIS package for Visual Studio Code
- [node-makensis](https://www.npmjs.com/package/makensis) - Node wrapper for `makensis`
- [atom-language-nsis](https://atom.io/packages/language-nsis) - NSIS package for Atom

## License

This work is dual-licensed under [The MIT License](https://opensource.org/licenses/MIT) and the [GNU General Public License, version 2.0](https://opensource.org/licenses/GPL-2.0)
