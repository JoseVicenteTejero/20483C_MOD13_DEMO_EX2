# 20483C_MOD13_DEMO_EX2
Lesson 2:   Implementing Asymmetric Encryption

JOSE VICENTE TEJERO CALDERERA - 06/11/2020

RESUMEN
Demonstration:  Encrypting and Decrypting Grade Reports Lab


PROBLEMAS
Al ejecutar pide el path donde están los ficheros encriptados, al pulsar "print" no hace nada mostrando la ejecución los siguientes mensajes:

School.exe' (CLR v4.0.30319: DefaultDomain): Loaded 'C:\WINDOWS\Microsoft.Net\assembly\GAC_32\mscorlib\v4.0_4.0.0.0__b77a5c561934e089\mscorlib.dll'. Skipped loading symbols. Module is optimized and the debugger option 'Just My Code' is enabled.
'School.exe' (CLR v4.0.30319: DefaultDomain): Loaded 'C:\20483\Allfiles\Mod13\Labfiles\Solution\Exercise 2\School-Reports\bin\Debug\School.exe'. Symbols loaded.
'School.exe' (CLR v4.0.30319: School.exe): Loaded 'C:\WINDOWS\Microsoft.Net\assembly\GAC_MSIL\PresentationFramework\v4.0_4.0.0.0__31bf3856ad364e35\PresentationFramework.dll'. Skipped loading symbols. Module is optimized and the debugger option 'Just My Code' is enabled.
'School.exe' (CLR v4.0.30319: School.exe): Loaded 'C:\WINDOWS\Microsoft.Net\assembly\GAC_MSIL\WindowsBase\v4.0_4.0.0.0__31bf3856ad364e35\WindowsBase.dll'. Skipped loading symbols. Module is optimized and the debugger option 'Just My Code' is enabled.
'School.exe' (CLR v4.0.30319: School.exe): Loaded 'C:\WINDOWS\Microsoft.Net\assembly\GAC_MSIL\System.Core\v4.0_4.0.0.0__b77a5c561934e089\System.Core.dll'. Skipped loading symbols. Module is optimized and the debugger option 'Just My Code' is enabled.
'School.exe' (CLR v4.0.30319: School.exe): Loaded 'C:\WINDOWS\Microsoft.Net\assembly\GAC_MSIL\System\v4.0_4.0.0.0__b77a5c561934e089\System.dll'. Skipped loading symbols. Module is optimized and the debugger option 'Just My Code' is enabled.
'School.exe' (CLR v4.0.30319: School.exe): Loaded 'C:\WINDOWS\Microsoft.Net\assembly\GAC_32\PresentationCore\v4.0_4.0.0.0__31bf3856ad364e35\PresentationCore.dll'. Skipped loading symbols. Module is optimized and the debugger option 'Just My Code' is enabled.
'School.exe' (CLR v4.0.30319: School.exe): Loaded 'C:\WINDOWS\Microsoft.Net\assembly\GAC_MSIL\System.Xaml\v4.0_4.0.0.0__b77a5c561934e089\System.Xaml.dll'. Skipped loading symbols. Module is optimized and the debugger option 'Just My Code' is enabled.
'School.exe' (CLR v4.0.30319: School.exe): Loaded 'C:\Program Files (x86)\Microsoft Visual Studio\2019\Community\Common7\IDE\PrivateAssemblies\Runtime\Microsoft.VisualStudio.Debugger.Runtime.dll'. Skipped loading symbols. Module is optimized and the debugger option 'Just My Code' is enabled.
'School.exe' (CLR v4.0.30319: School.exe): Loaded 'C:\WINDOWS\Microsoft.Net\assembly\GAC_MSIL\System.Configuration\v4.0_4.0.0.0__b03f5f7f11d50a3a\System.Configuration.dll'. Skipped loading symbols. Module is optimized and the debugger option 'Just My Code' is enabled.
'School.exe' (CLR v4.0.30319: School.exe): Loaded 'C:\WINDOWS\Microsoft.Net\assembly\GAC_MSIL\System.Xml\v4.0_4.0.0.0__b77a5c561934e089\System.Xml.dll'. Skipped loading symbols. Module is optimized and the debugger option 'Just My Code' is enabled.
Step into: Stepping over non-user code 'School.App..ctor'
Step into: Stepping over non-user code 'School.App.InitializeComponent'
'School.exe' (CLR v4.0.30319: School.exe): Loaded 'C:\WINDOWS\Microsoft.Net\assembly\GAC_MSIL\mscorlib.resources\v4.0_4.0.0.0_es_b77a5c561934e089\mscorlib.resources.dll'. Module was built without symbols.
'School.exe' (CLR v4.0.30319: School.exe): Loaded 'C:\WINDOWS\assembly\GAC_MSIL\Microsoft.Office.Interop.Word\15.0.0.0__71e9bce111e9429c\Microsoft.Office.Interop.Word.dll'. Module was built without symbols.
'School.exe' (CLR v4.0.30319: School.exe): Loaded 'C:\WINDOWS\assembly\GAC_MSIL\office\15.0.0.0__71e9bce111e9429c\office.dll'. Module was built without symbols.
'School.exe' (CLR v4.0.30319: School.exe): Loaded 'C:\WINDOWS\Microsoft.Net\assembly\GAC_MSIL\PresentationFramework.Aero2\v4.0_4.0.0.0__31bf3856ad364e35\PresentationFramework.Aero2.dll'. Skipped loading symbols. Module is optimized and the debugger option 'Just My Code' is enabled.
'School.exe' (CLR v4.0.30319: School.exe): Loaded 'C:\WINDOWS\Microsoft.Net\assembly\GAC_MSIL\PresentationFramework.resources\v4.0_4.0.0.0_es_31bf3856ad364e35\PresentationFramework.resources.dll'. Module was built without symbols.
'School.exe' (CLR v4.0.30319: School.exe): Loaded 'C:\WINDOWS\Microsoft.Net\assembly\GAC_MSIL\PresentationFramework-SystemXml\v4.0_4.0.0.0__b77a5c561934e089\PresentationFramework-SystemXml.dll'. Skipped loading symbols. Module is optimized and the debugger option 'Just My Code' is enabled.
'School.exe' (CLR v4.0.30319: School.exe): Loaded 'C:\WINDOWS\Microsoft.Net\assembly\GAC_MSIL\PresentationCore.resources\v4.0_4.0.0.0_es_31bf3856ad364e35\PresentationCore.resources.dll'. Module was built without symbols.
'School.exe' (CLR v4.0.30319: School.exe): Loaded 'c:\program files (x86)\microsoft visual studio\2019\community\common7\ide\commonextensions\microsoft\xamldiagnostics\Framework\x86\Microsoft.VisualStudio.DesignTools.WpfTap.dll'. Skipped loading symbols. Module is optimized and the debugger option 'Just My Code' is enabled.
'School.exe' (CLR v4.0.30319: School.exe): Loaded 'C:\WINDOWS\Microsoft.Net\assembly\GAC_MSIL\System.Runtime.Serialization\v4.0_4.0.0.0__b77a5c561934e089\System.Runtime.Serialization.dll'. Skipped loading symbols. Module is optimized and the debugger option 'Just My Code' is enabled.
'School.exe' (CLR v4.0.30319: School.exe): Loaded 'C:\WINDOWS\Microsoft.Net\assembly\GAC_MSIL\SMDiagnostics\v4.0_4.0.0.0__b77a5c561934e089\SMDiagnostics.dll'. Skipped loading symbols. Module is optimized and the debugger option 'Just My Code' is enabled.
'School.exe' (CLR v4.0.30319: School.exe): Loaded 'C:\WINDOWS\Microsoft.Net\assembly\GAC_MSIL\System.ServiceModel.Internals\v4.0_4.0.0.0__31bf3856ad364e35\System.ServiceModel.Internals.dll'. Skipped loading symbols. Module is optimized and the debugger option 'Just My Code' is enabled.
'School.exe' (CLR v4.0.30319: School.exe): Loaded 'C:\WINDOWS\Microsoft.Net\assembly\GAC_MSIL\UIAutomationTypes\v4.0_4.0.0.0__31bf3856ad364e35\UIAutomationTypes.dll'. Skipped loading symbols. Module is optimized and the debugger option 'Just My Code' is enabled.
'School.exe' (CLR v4.0.30319: School.exe): Loaded 'C:\WINDOWS\Microsoft.Net\assembly\GAC_MSIL\UIAutomationProvider\v4.0_4.0.0.0__31bf3856ad364e35\UIAutomationProvider.dll'. Skipped loading symbols. Module is optimized and the debugger option 'Just My Code' is enabled.
'School.exe' (CLR v4.0.30319: School.exe): Loaded 'C:\WINDOWS\Microsoft.Net\assembly\GAC_MSIL\System.Runtime.Serialization.resources\v4.0_4.0.0.0_es_b77a5c561934e089\System.Runtime.Serialization.resources.dll'. Module was built without symbols.
'School.exe' (CLR v4.0.30319: School.exe): Loaded 'C:\WINDOWS\Microsoft.Net\assembly\GAC_MSIL\System.Windows.Forms\v4.0_4.0.0.0__b77a5c561934e089\System.Windows.Forms.dll'. Skipped loading symbols. Module is optimized and the debugger option 'Just My Code' is enabled.
'School.exe' (CLR v4.0.30319: School.exe): Loaded 'C:\WINDOWS\Microsoft.Net\assembly\GAC_MSIL\System.Drawing\v4.0_4.0.0.0__b03f5f7f11d50a3a\System.Drawing.dll'. Skipped loading symbols. Module is optimized and the debugger option 'Just My Code' is enabled.
'School.exe' (CLR v4.0.30319: School.exe): Loaded 'C:\WINDOWS\Microsoft.Net\assembly\GAC_MSIL\Accessibility\v4.0_4.0.0.0__b03f5f7f11d50a3a\Accessibility.dll'. 
Exception thrown: 'System.OutOfMemoryException' in School.exe
An unhandled exception of type 'System.OutOfMemoryException' occurred in School.exe


Excepción no controlada: OutOfMemoryException.
The program '[44068] School.exe' has exited with code 0 (0x0).
