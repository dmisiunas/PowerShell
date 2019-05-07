
$ip='10.10.10.10'
$b=""
$a= Get-ItemProperty -Path "Registry::HKCU\Software\Microsoft\Windows\CurrentVersion\Internet Settings"
if ($a.ProxyOverride -cmatch $ip)
  {
Write-Host $ip "value already exist"
  }
else
   {
    Write-Host $ip "value not found and record will be modified "
    $b= $a.ProxyOverride -replace "<local>","$ip;<local>"
    Set-ItemProperty -Path "Registry::HKCU\Software\Microsoft\Windows\CurrentVersion\Internet Settings" ProxyOverride -value $b
   }
