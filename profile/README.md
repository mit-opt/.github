## MIT-OPT

### Interface Messages

#### From MOOS:

   * DESIRED_WAMV_STATE int  

   * DESIRED_HEADING degrees 

   * DESIRED_SPEED m/s

   * DESIRED_ENG_STATUS_STDB bool

   * DESIRED_ENG_STATUS_PORT bool  

   

#### FROM WAMV: 

   * WAMV_STATE int

   * NAV_STATE: string
     * NAV_SPEED  m/s
     * NAV_HEADING degrees
     * NAV_LAT float
     * NAV_LONG float

   * ENG_STATUS_STDB bool

   * ENG_STATUS_PORT bool
