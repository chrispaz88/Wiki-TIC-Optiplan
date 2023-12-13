
Video Guía
https://www.youtube.com/watch?v=mUEeUT5AusQ&t=1s

**Propiedades del Servidor**
<table>
<thead>
<tr>
<th>sku.name</th>
<th>sku.tier</th>
<th>systemData.createdAt</th>
<th>properties.authConfig.activeDirectoryAuth</th>
<th>properties.authConfig.passwordAuth</th>
<th>properties.dataEncryption.type</th>
<th>properties.fullyQualifiedDomainName</th>
<th>properties.version</th>
<th>properties.minorVersion</th>
<th>properties.administratorLogin</th>
<th>properties.state</th>
<th>properties.availabilityZone</th>
<th>properties.storage.storageSizeGB</th>
<th>properties.backup.backupRetentionDays</th>
<th>properties.backup.geoRedundantBackup</th>
<th>properties.backup.earliestRestoreDate</th>
<th>properties.network.publicNetworkAccess</th>
<th>properties.highAvailability.mode</th>
<th>properties.highAvailability.state</th>
<th>properties.maintenanceWindow.customWindow</th>
<th>properties.maintenanceWindow.dayOfWeek</th>
<th>properties.maintenanceWindow.startHour</th>
<th>properties.maintenanceWindow.startMinute</th>
<th>properties.replicationRole</th>
<th>properties.replicaCapacity</th>
<th>location</th>
<th>id</th>
<th>name</th>
<th>type</th>
</tr>
</thead>
<tbody>
<tr>
<td>Standard_B1ms</td>
<td>Burstable</td>
<td>2023-12-13T14:37:17.5355776Z</td>
<td>Disabled</td>
<td>Enabled</td>
<td>SystemManaged</td>
<td>optiplandb.postgres.database.azure.com</td>
<td>16</td>
<td>0</td>
<td>admin_optiplan</td>
<td>Ready</td>
<td>3</td>
<td>32</td>
<td>7</td>
<td>Disabled</td>
<td>2023-12-13T14:42:36.9399697+00:00</td>
<td>Enabled</td>
<td>Disabled</td>
<td>NotEnabled</td>
<td>Disabled</td>
<td>0</td>
<td>0</td>
<td>0</td>
<td>Primary</td>
<td>5</td>
<td>East US</td>
<td>/subscriptions/e29d9c97-2e94-486d-9e86-47021bbf5fc0/resourceGroups/PostgresSQL/providers/Microsoft.DBforPostgreSQL/flexibleServers/optiplandb</td>
<td>optiplandb</td>
<td>Microsoft.DBforPostgreSQL/flexibleServers</td>
</tr>
</tbody>
</table>


**Detalles de Conexión**

Establezca las siguientes variables de entorno copiando y pegando las líneas siguientes en el terminal de Bash (WSL, Azure Cloud Shell, etc.).

`export PGHOST=optiplandb.postgres.database.azure.com`
`export PGUSER=admin_optiplan`
`export PGPORT=5432`
`export PGPORT=5432`
`export PGPASSWORD="{your-password}"`
