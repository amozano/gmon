**Client**
  * Traffic is ALWAYS from client -> server (encrypted)
  * Will report to server at specified intervals
  * Will report on CPU, DISK, LOAD etc. etc.
  * Will be able to use plugins from Nagios and perlscripts
  * Will be told by server what to check for
  * Will be able to update itself and plugins
  * NFS/SAMBA/”Windows network filesystem” client support (dir for each hostname-macaddress)
  * Application performance statistics (PerformanceGuard)
  * RemoteConnection (TightVNC + RemoteDesktop + SessionManagement)

**Server**
  * A daemon (perl/ruby) with a database (postgres)
  * Collect data from clients
  * Status
  * Statistics
  * Webchecks (with historical data from Webarchive + Netcraft)

**WebServer**
  * Configure new hosts
  * Download client
  * Configure what clients should check for
  * See current status
  * See statistics
  * See log of events
  * Audit trail (see historical configuration changes)
  * Notification (Wave + IM + Mail + SMS)
  * Configure Users and Groups (LDAP + NIS integration)
  * Overview
  * Maps (Googlemap with AutoZoom & RouteTo -> Serverroom floorplan drawing -> rack -> server)
  * Network drawing (route and statistics between equipment/segments/sites)
  * Status toolbar (Firefox)
  * ConfigurationManagement (autoinstall softwarepackages)
  * Documentation management (Wave + Subversion)
  * ServiceLevel management with service reports
  * Servicedesk parser (Wave + IssueTracker + Remedy + RequestTracker)