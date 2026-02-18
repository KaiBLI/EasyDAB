# This Folder Contains Exported and Cleaned Up Bill of Materials Sheets.

The EasyDAB BoM W. Assembly Opts is the Sheet you will want to utilize when sourcing components. This BoM has separated out the SFN Option into the individualized options of the VCTCXO and Extra SRAM. This may apply if someone who has no need for SFN but wants a more accurate oscillator or the additional SRAMs.

For SFN You will need to obtain and install the components for the below lists:
EasyDAB Main
VCTCXO
Extra SRAM
GPS

I -STRONGLY- advise you to install the Extra SRAMs. There is potentially an issue where the current SFN-Enabled firmware is too bulky to maintain a sufficient buffer with the main SRAM only. Additionally, the exciter will stop broadcasting if you interact with the management page when you lack the additional SRAM. Production use warrants the use of extra SRAM for that reason alone. Additionally, if your DAB Mux server is fairly remote to the exciter, the additional buffer provided by the extra SRAMs is also needed for that too. 

If you are planning for production or long term use, I would also encourage you to use a VCTCXO to ensure accurate modulation of your digital signal. The quartz oscillator 'works', but probably best for experimental use only. 

If you do not need to do a single-frequency network, which is likely if you are broadcasting over a small area, you should not install the GPS. If you later change your mind, you can always add it later. The u-Blox NEO GPS module is a fairly expensive part and is only used for SFN, so don't buy it if you don't need SFN!
