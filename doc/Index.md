VS Project System Documentation
===============================

- [Introduction](overview/intro.md)
- [Your obligations as a project system extender](overview/obligations.md)
- [Prerequisites](overview/prereqs.md)
- [Define a new project type](overview/define_a_new_project_type.md)
- [Extend/flavor an existing project type](overview/extend_an_existing_project_type.md)
- [Reference implementations](overview/reference_implementations.md)
- [Overview](overview/index.md)
  - [CPS Core vs. CPS VS](overview/CPS_Core_vs._CPS_VS.md)
  - [MEF](overview/mef.md)
  - [Scopes](overview/scopes.md)
  - [Project Capabilities](overview/about_project_capabilities.md)
  - [Dynamic Capabilities](overview/dynamicCapabilities.md)
  - [Interfaces defined on IVsProject object](overview/interfaces_defined_on_IVsProject_object.md)
  - [Interfaces NOT defined on IVsProject object](overview/interfaces_NOT_defined_on_IVsProject_object.md)
  - [The Project Lock](overview/project_lock.md)
  - [Project configurations](overview/project_configurations.md)
  - [Content/item types](overview/contentitem_types.md)
  - [Accessing IVsHierarchy from CPS](overview/access_IVsHierarchy_from_cps.md)
    - [ItemIDs](overview/ItemIDs.md)
  - [Responsive design](overview/responsive_design.md)
  - [Globbing behavior](overview/globbing_behavior.md)
  - [Dataflow](overview/dataflow.md)
    - [Dataflow in CPS](overview/dataflow_in_CPS.md)
    - [Dataflow source blocks](extensibility/dataflow_sources.md)
  - Diagnostics
    - [How to examine Visual Studio registry](overview/examine_registry.md)
    - [How to enable logging](overview/enable_logging.md)
- [Threading model](overview/threading_model.md)
  - [Threading Rules](overview/threading_rules.md)
  - [CookBook](overview/cookbook.md)
- Clients / Automation
  - [Detect whether a project is a CPS project](automation/detect_whether_a_project_is_a_CPS_project.md)
  - [Finding CPS in a VS project](automation/finding_CPS_in_a_VS_project.md)
  - [Obtaining the IProjectService/ProjectService](automation/obtaining_the_ProjectService.md)
  - [Obtaining the IProjectLockService](automation/obtaining_the_IProjectLockService.md)
  - [Obtaining the IProjectThreadingService service](automation/obtaining_the_IThreadHandling_service.md)
  - [Obtaining the MSBuild.Project from CPS](automation/obtaining_the_MSBuild.Project_from_CPS.md)
  - [Query output groups](automation/query_output_groups.md)
  - [Subscribe to project data](automation/subscribe_to_project_data.md)
  - [Notification for async project load completion](automation/notification_for_async_project_load_completion.md)
  - [Sync up shims to latest project model](automation/sync_shims_to_latest_project_model.md)
  - [Add a source item with specific item type](automation/add_a_source_item_with_specific_item_type.md)
  - Behavioral differences between CPS and other project systems
      - [GetMkDocument returns ">12" style strings](automation/GetMkDocument_returns_12_style_strings.md)
- [Extensibility points](extensibility/index.md)
  - [Item Templates](extensibility/project_item_templates.md)
  - [Custom item types](extensibility/custom_item_types.md)
  - [Custom reference types](extensibility/custom_reference_types.md)
  - [IDebugLaunchProvider](extensibility/IDebugLaunchProvider.md)
  - [IDeployProvider](extensibility/IDeployProvider.md)
  - Properties
    - [Property pages](extensibility/property_pages.md)
    - [How to retrieve the value of a property](extensibility/property_retrievevalue.md)
    - [IDynamicEnumValuesProvider](extensibility/IDynamicEnumValuesProvider.md)
    - [Property value editors](extensibility/property_value_editors.md)
    - [Adding Xaml Rules](extensibility/adding_xaml_rules.md)
    - [Extending rules](extensibility/extending_rules.md)
  - [IBuildUpToDateCheckProvider](extensibility/IBuildUpToDateCheckProvider.md)
  - [IsDocumentInProject](extensibility/IsDocumentInProject.md)
  - [Automatic DependentUpon wire-up](extensibility/automatic_DependentUpon_wireup.md)
  - [Command handlers](extensibility/command_handlers.md)
  - [IProjectTreeProvider](extensibility/IProjectTreeProvider.md)
  - [IProjectTreePropertiesProvider](extensibility/IProjectTreePropertiesProvider.md)
  - [IPublishProvider](extensibility/IPublishProvider.md)
  - [IProfilableProjectProvider](extensibility/IProfilableProjectProvider.md)
  - [Clipboard](extensibility/clipboard.md)
  - [IValidProjectReferenceChecker](extensibility/IValidProjectReferenceChecker.md)
  - [IProjectSourceItemProviderExtension](extensibility/IProjectSourceItemProviderExtension.md)
  - [IProjectItemContextMenuProvider](extensibility/IProjectItemContextMenuProvider.md)
  - [IProjectPropertiesProvider](extensibility/IProjectPropertiesProvider.md)
  - [IProjectGlobalPropertiesProvider](extensibility/IProjectGlobalPropertiesProvider.md)
  - [IFileSystemErrorMessageProvider](extensibility/IFileSystemErrorMessageProvider.md)
  - [IBuildLoggerProvider](extensibility/IBuildLoggerProvider.md)
  - [IProjectCapabilitiesProvider](extensibility/IProjectCapabilitiesProvider.md)
  - [Reference Manager](extensibility/reference_manager.md)
- How do I?
  - [Provide custom icons for the Project Type/Item type](scenario/provide_custom_icons_for_the_project_or_item_type.md)
  - [Appropriately schedule async tasks](scenario/appropriately_schedule_async_tasks.md)
  - [Block/Defer critical project operations](scenario/defer_critical_project_operations.md)
  - [Analyze Hangs](scenario/analyze_hangs.md)
     - [Who holds a project lock?](scenario/who_holds_a_project_lock.md)
  - [Turn on CPS for a C#/VB project](scenario/turn_on_cps_for_csharp_vb_project.md)
  - [Add Single File Generator](scenario/add_single_file_generator.md)
- Breaking changes
  - [Breaking Changes in Visual Studio 2019](overview/breaking_changes_visual_studio_2019.md)
  - [Breaking Changes in Visual Studio 2017](overview/breaking_changes_visual_studio_2017.md)
  - [Breaking changes in Visual Studio 2015](overview/VS2013_vs_VS2015.md)
  - [VS2015 docs](https://github.com/microsoft/VSProjectSystem/commit/eea4b8528b6008099641980392a12fcf8d0be186)
