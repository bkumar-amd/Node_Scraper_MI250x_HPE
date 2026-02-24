# Error_Scrapper_MI250x_HPE
Error scrapper plugin config file for ProcessPlugin , StoragePlugin , MemoryPlugin in MI250x HPE nodes

Command to Run Error Scrapper on Lockhart MI250x node

pip install amd-node-scraper

node-scraper --plugin-configs lockhart_MI250x_ErrorScrapper_config.json -- run-plugins \
  AmdSmiPlugin BiosPlugin CmdlinePlugin DeviceEnumerationPlugin DimmPlugin \
  DkmsPlugin DmesgPlugin JournalPlugin KernelPlugin KernelModulePlugin \
  NetworkPlugin OsPlugin PackagePlugin PciePlugin RocmPlugin \
  AmdSmiPlugin BiosPlugin CmdlinePlugin DeviceEnumerationPlugin DimmPlugin \
  DkmsPlugin DmesgPlugin JournalPlugin KernelPlugin KernelModulePlugin \
  NetworkPlugin OsPlugin PackagePlugin PciePlugin RocmPlugin \
  SysctlPlugin SyslogPlugin UptimePlugin
