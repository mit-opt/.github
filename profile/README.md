## MIT-OPT

### Interface Messages

#### From MOOS-IvP:

   * DESIRED_WAMV_STATE (int)
     * 1: Connected to WAM-V?
     * 2:
     * 3: Drive?     

   * DESIRED_HEADING (degrees)
     * 0-360  

   * DESIRED_SPEED (m/s)

   * DESIRED_ENG_STATUS_STDB (bool)
     * 0: Off
     * 1: On 

   * DESIRED_ENG_STATUS_PORT (bool)
     * 0: Off
     * 1: ON

   

#### FROM OPT WAM-V: 

   * WAMV_STATE (int)

   * NAV_STATE: (string)
     * NAV_SPEED  (m/s)
     * NAV_HEADING (degrees)
     * NAV_LAT (double)
     * NAV_LONG (double)
     * EX: "NAV_SPEED=`<m/s>`,NAV_HEADING=`<deg>`,NAV_LAT=`<double>`,NAV_LONG=`<double>`"

   * ENG_STATUS_STDB (bool)

   * ENG_STATUS_PORT (bool)
     
   * STATION_KEEP_UPDATE (string)
     * LAT (double)
     * LONG (double)
     * RADIUS (drift radius, in meters, around station point)
     * Ex: "LAT=`<double>`,LONG=`<double>`,RADIUS=`<meters>`"
    
   * WAYPOINT_UPDATE (string)
     * LAT (double)
     * LONG (double)
     * EX: "LAT=`<double>`,LONG=`<double>`,...,LAT=`<double>`,LONG=`<double>`"
