# COVID-19 RKI Munin Plugin

This plugin parses the XSLX structure of the current vaccination counts of the Robert Koch Institute to display in a munin graph. The plugin does not do the downloading.

Disclaimer: This was done quick and dirty!

# Install

The plugin requires openpyxl==2.6.4.

Set `EXCEL_DUMP_PATH` to your path where the XLSX files are stored and make sure the xlsx files are named by their date's (e. g. with `$(date +%d.%m.%y).xlsx`) and paste the plugin into munins plugin directory. Make sure you set `+x` to the plugin to make it executable.

# LICENSE

MIT