# NOde_Scrapper_MI250x_HPE
Error scrapper plugin config file for ProcessPlugin , StoragePlugin , MemoryPlugin in MI250x HPE nodes

Command to Run Node Scrapper on Lockhart MI250x node

git clone https://github.com/bkumar-amd/Node_Scraper_MI250x_HPE.git

pip install amd-node-scraper

node-scraper --plugin-configs lockhart_MI250x_NodeScrapper_config.json -- run-plugins \
  AmdSmiPlugin BiosPlugin CmdlinePlugin DeviceEnumerationPlugin DimmPlugin \
  DkmsPlugin DmesgPlugin JournalPlugin KernelPlugin KernelModulePlugin \
  NetworkPlugin OsPlugin PackagePlugin PciePlugin RocmPlugin \
  AmdSmiPlugin BiosPlugin CmdlinePlugin DeviceEnumerationPlugin DimmPlugin \
  DkmsPlugin DmesgPlugin JournalPlugin KernelPlugin KernelModulePlugin \
  NetworkPlugin OsPlugin PackagePlugin PciePlugin RocmPlugin \
  SysctlPlugin SyslogPlugin UptimePlugin
