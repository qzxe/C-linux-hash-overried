# C-linux-hash-overried
Endpoints // 

onLanguage:c
onLanguage:cpp
onLanguage:cuda-cpp
onCommand:extension.pickNativeProcess
onCommand:extension.pickRemoteNativeProcess
onCommand:C_Cpp.BuildAndDebugActiveFile
onCommand:C_Cpp.ConfigurationEditJSON
onCommand:C_Cpp.ConfigurationEditUI
onCommand:C_Cpp.ConfigurationSelect
onCommand:C_Cpp.ConfigurationProviderSelect
onCommand:C_Cpp.SwitchHeaderSource
onCommand:C_Cpp.EnableErrorSquiggles
onCommand:C_Cpp.DisableErrorSquiggles
onCommand:C_Cpp.ToggleIncludeFallback
onCommand:C_Cpp.ToggleDimInactiveRegions
onCommand:C_Cpp.ResetDatabase
onCommand:C_Cpp.TakeSurvey
onCommand:C_Cpp.LogDiagnostics
onCommand:C_Cpp.RescanWorkspace
onCommand:C_Cpp.VcpkgClipboardInstallSuggested
onCommand:C_Cpp.VcpkgOnlineHelpSuggested
onCommand:C_Cpp.GenerateEditorConfig
onCommand:C_Cpp.GoToNextDirectiveInGroup
onCommand:C_Cpp.GoToPrevDirectiveInGroup
onCommand:C_Cpp.CheckForCompiler
onDebugInitialConfigurations
onDebugResolve:cppdbg
onDebugResolve:cppvsdbg
workspaceContains:/.vscode/c_cpp_properties.json
onFileSystem:cpptools-schema

Endpoints HTML //

$ curl "https://gitlab.com/api/v4/projects" | less
$ curl --form "avatar=@me.jpg" "https://example.com/api/v4/endpoint"
$ curl --request PUT \
--header "PRIVATE-TOKEN: your_access_token_here" \
--data "long=true" \
--data "per_page=10" \
"https://example.com/api/v4/namespaces"
