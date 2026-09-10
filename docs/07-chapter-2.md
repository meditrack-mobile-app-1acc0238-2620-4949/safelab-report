# **Chapter II: Requirements Development and Software Solution Design**
## **2.1. Competitors**
### **2.1.1. Competitive Analysis**
### **2.1.2. Strategies and Tactics Against Competitors**
## **2.2. Interviews**
### **2.2.1. Interview Design**
### **2.2.2. Interview Recording**
### **2.2.3. Interview Analysis**
## **2.3. Needfinding**
### **2.3.1. User Personas**
### **2.3.2. User Task Matrix**
### **2.3.3. User Journey Mapping**
### **2.3.4. Empathy Mapping**
### **2.3.5. Big Picture Event Storming**
### **2.3.6. Ubiquitous Language**
## **2.4. Requirements Specification**
### **2.4.1. User Stories**
<p style="text-align: justify;">
  This section presents the Epics, User Stories, Technical Stories, and Spike Stories identified for SafeLab according to the needs of Hospital Laboratories and Pharmaceutical Companies. The Acceptance Criteria are written using the Given-When-Then structure to establish verifiable conditions for each requirement without depending on specific user interface details.
</p>

#### **Epics**

<table style="width: 100%; border-collapse: collapse;">
  <tr>
    <th>Epic ID</th>
    <th>Title</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>EP01</td>
    <td>Monitoring Organization</td>
    <td>Manage monitoring sites, storage areas, and equipment to organize environmental monitoring across locations.</td>
  </tr>
  <tr>
    <td>EP02</td>
    <td>Real-Time Monitoring</td>
    <td>View temperature, humidity, equipment status, and monitoring information automatically without relying on manual recording.</td>
  </tr>
  <tr>
    <td>EP03</td>
    <td>Alerts and Notifications</td>
    <td>Receive, view, and manage alerts related to environmental conditions and monitored equipment.</td>
  </tr>
  <tr>
    <td>EP04</td>
    <td>Reporting and Data Analysis</td>
    <td>Access historical data, compare periods, and generate reports to support monitoring, control, and auditing.</td>
  </tr>
  <tr>
    <td>EP05</td>
    <td>Equipment Condition and Maintenance</td>
    <td>Monitor equipment condition, reliability, and maintenance history to identify potential failures.</td>
  </tr>
  <tr>
    <td>EP06</td>
    <td>Dashboard and System Overview</td>
    <td>Provide a centralized summary of monitoring information, alerts, and relevant indicators.</td>
  </tr>
  <tr>
    <td>EP07</td>
    <td>User Access and Roles</td>
    <td>Allow users to access SafeLab and manage account and access information.</td>
  </tr>
  <tr>
    <td>EP08</td>
    <td>Landing Page</td>
    <td>Present SafeLab and its product information through the static Landing Page.</td>
  </tr>
</table>

<br>

#### **User Stories**

##### **US01 - Register monitoring site**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US01</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP01</td></tr>
  <tr><th>Title</th><td colspan="3">Register monitoring site</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to register a monitoring site with its name and location so I can organize monitoring.</td></tr>
  <tr>
    <th>Acceptance Criteria</th>
    <td colspan="3">
      <b>Scenario 1: Successful registration</b><br>
      <b>Given</b> that valid site information is provided<br>
      <b>When</b> the user registers the monitoring site<br>
      <b>Then</b> the system stores the site information.<br><br>
      <b>Scenario 2: Required information is missing</b><br>
      <b>Given</b> that required site information is incomplete<br>
      <b>When</b> the user attempts to register the monitoring site<br>
      <b>Then</b> the system rejects the registration.
    </td>
  </tr>
</table>

##### **US02 - View monitoring sites**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US02</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP01</td></tr>
  <tr><th>Title</th><td colspan="3">View monitoring sites</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to view the registered monitoring sites so I can manage them.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Registered sites exist</b><br>
    <b>Given</b> that monitoring sites are registered<br>
    <b>When</b> the user requests the registered sites<br>
    <b>Then</b> the system provides the available sites.<br><br>
    <b>Scenario 2: No sites are registered</b><br>
    <b>Given</b> that no monitoring sites are registered<br>
    <b>When</b> the user requests the registered sites<br>
    <b>Then</b> the system indicates that no sites are available.
  </td></tr>
</table>

##### **US03 - Create storage area**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US03</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP01</td></tr>
  <tr><th>Title</th><td colspan="3">Create storage area</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to create storage areas with a name and type so I can organize equipment.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Successful creation</b><br>
    <b>Given</b> that valid storage area information is provided<br>
    <b>When</b> the user creates the storage area<br>
    <b>Then</b> the system stores the new storage area.<br><br>
    <b>Scenario 2: Required information is missing</b><br>
    <b>Given</b> that required storage area information is incomplete<br>
    <b>When</b> the user attempts to create the storage area<br>
    <b>Then</b> the system rejects the creation.
  </td></tr>
</table>

##### **US04 - View storage areas**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US04</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>Medium</td><th>Epic</th><td>EP01</td></tr>
  <tr><th>Title</th><td colspan="3">View storage areas</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to view storage areas so I can understand how monitored equipment is organized.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Storage areas exist</b><br>
    <b>Given</b> that storage areas are registered<br>
    <b>When</b> the user requests the storage areas<br>
    <b>Then</b> the system provides the registered storage areas.<br><br>
    <b>Scenario 2: No storage areas exist</b><br>
    <b>Given</b> that no storage areas are registered<br>
    <b>When</b> the user requests the storage areas<br>
    <b>Then</b> the system indicates that no storage areas are available.
  </td></tr>
</table>

##### **US05 - Register equipment**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US05</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP01</td></tr>
  <tr><th>Title</th><td colspan="3">Register equipment</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to register equipment with its name, type, and identifier so it can be monitored.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Successful registration</b><br>
    <b>Given</b> that valid equipment information is provided<br>
    <b>When</b> the user registers the equipment<br>
    <b>Then</b> the system stores the equipment information.<br><br>
    <b>Scenario 2: Required information is missing</b><br>
    <b>Given</b> that required equipment information is incomplete<br>
    <b>When</b> the user attempts to register the equipment<br>
    <b>Then</b> the system rejects the registration.
  </td></tr>
</table>

##### **US06 - View equipment list**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US06</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP01</td></tr>
  <tr><th>Title</th><td colspan="3">View equipment list</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to view registered equipment so I can manage it.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Equipment exists</b><br>
    <b>Given</b> that equipment is registered<br>
    <b>When</b> the user requests the equipment list<br>
    <b>Then</b> the system provides the registered equipment.<br><br>
    <b>Scenario 2: No equipment exists</b><br>
    <b>Given</b> that no equipment is registered<br>
    <b>When</b> the user requests the equipment list<br>
    <b>Then</b> the system indicates that no equipment is available.
  </td></tr>
</table>

##### **US07 - Assign equipment to area**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US07</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP01</td></tr>
  <tr><th>Title</th><td colspan="3">Assign equipment to area</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to assign equipment to a storage area so I know its location.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Valid equipment and area are provided</b><br>
    <b>Given</b> that registered equipment and a registered storage area exist<br>
    <b>When</b> the user assigns the equipment to the storage area<br>
    <b>Then</b> the system associates the equipment with that area.<br><br>
    <b>Scenario 2: Required information is unavailable</b><br>
    <b>Given</b> that the equipment or storage area is not available<br>
    <b>When</b> the user attempts to create the assignment<br>
    <b>Then</b> the system rejects the assignment.
  </td></tr>
</table>

##### **US08 - Search equipment by name**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US08</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>Medium</td><th>Epic</th><td>EP01</td></tr>
  <tr><th>Title</th><td colspan="3">Search equipment by name</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to search equipment by name so I can find it quickly.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Matching equipment exists</b><br>
    <b>Given</b> that registered equipment matches the provided name<br>
    <b>When</b> the user performs the search<br>
    <b>Then</b> the system provides the matching equipment.<br><br>
    <b>Scenario 2: No matching equipment exists</b><br>
    <b>Given</b> that no registered equipment matches the provided name<br>
    <b>When</b> the user performs the search<br>
    <b>Then</b> the system indicates that no matching equipment is available.
  </td></tr>
</table>

##### **US09 - View temperature values**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US09</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP02</td></tr>
  <tr><th>Title</th><td colspan="3">View temperature values</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to view temperature values so I can monitor storage conditions.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Temperature data is available</b><br>
    <b>Given</b> that monitored equipment has temperature data<br>
    <b>When</b> the user requests its monitoring information<br>
    <b>Then</b> the system provides the available temperature value.<br><br>
    <b>Scenario 2: Temperature data is unavailable</b><br>
    <b>Given</b> that monitored equipment does not have available temperature data<br>
    <b>When</b> the user requests its monitoring information<br>
    <b>Then</b> the system indicates that temperature data is unavailable.
  </td></tr>
</table>

##### **US10 - View humidity values**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US10</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP02</td></tr>
  <tr><th>Title</th><td colspan="3">View humidity values</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to view humidity values so I can monitor storage conditions.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Humidity data is available</b><br>
    <b>Given</b> that monitored equipment has humidity data<br>
    <b>When</b> the user requests its monitoring information<br>
    <b>Then</b> the system provides the available humidity value.<br><br>
    <b>Scenario 2: Humidity data is unavailable</b><br>
    <b>Given</b> that monitored equipment does not have available humidity data<br>
    <b>When</b> the user requests its monitoring information<br>
    <b>Then</b> the system indicates that humidity data is unavailable.
  </td></tr>
</table>

##### **US11 - View equipment working status**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US11</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP02</td></tr>
  <tr><th>Title</th><td colspan="3">View equipment working status</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to know whether monitored equipment is working so I can detect issues.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Equipment is providing data</b><br>
    <b>Given</b> that the equipment is providing monitoring data<br>
    <b>When</b> the user requests its status<br>
    <b>Then</b> the system identifies the equipment as working.<br><br>
    <b>Scenario 2: Equipment is not providing data</b><br>
    <b>Given</b> that the equipment is not providing monitoring data<br>
    <b>When</b> the user requests its status<br>
    <b>Then</b> the system identifies that the equipment is not working normally.
  </td></tr>
</table>

##### **US12 - View equipment details**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US12</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP02</td></tr>
  <tr><th>Title</th><td colspan="3">View equipment details</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to view equipment details so I can review its temperature, humidity, and status.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Equipment exists</b><br>
    <b>Given</b> that registered equipment exists<br>
    <b>When</b> the user requests its details<br>
    <b>Then</b> the system provides its available temperature, humidity, and status information.<br><br>
    <b>Scenario 2: Equipment does not exist</b><br>
    <b>Given</b> that the requested equipment is not registered<br>
    <b>When</b> its details are requested<br>
    <b>Then</b> the system indicates that the equipment is unavailable.
  </td></tr>
</table>

##### **US13 - View equipment list with real-time data**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US13</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP02</td></tr>
  <tr><th>Title</th><td colspan="3">View equipment list with real-time data</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to view equipment with its current monitoring values so I can monitor conditions quickly.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Current monitoring data is available</b><br>
    <b>Given</b> that registered equipment has current monitoring data<br>
    <b>When</b> the user requests the equipment information<br>
    <b>Then</b> the system provides the equipment with its available current values.<br><br>
    <b>Scenario 2: Current data is unavailable</b><br>
    <b>Given</b> that some registered equipment does not have current data<br>
    <b>When</b> the user requests the equipment information<br>
    <b>Then</b> the system indicates which equipment does not have current data.
  </td></tr>
</table>

##### **US14 - Filter equipment by storage area**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US14</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>Medium</td><th>Epic</th><td>EP02</td></tr>
  <tr><th>Title</th><td colspan="3">Filter equipment by storage area</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to filter equipment by storage area so I can focus on a specific location.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Equipment exists in the selected area</b><br>
    <b>Given</b> that equipment is assigned to the selected storage area<br>
    <b>When</b> the user filters equipment by that area<br>
    <b>Then</b> the system provides the equipment assigned to it.<br><br>
    <b>Scenario 2: No equipment exists in the selected area</b><br>
    <b>Given</b> that no equipment is assigned to the selected storage area<br>
    <b>When</b> the user applies the filter<br>
    <b>Then</b> the system indicates that no equipment is available for that area.
  </td></tr>
</table>

##### **US15 - Identify equipment without recent data**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US15</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP02</td></tr>
  <tr><th>Title</th><td colspan="3">Identify equipment without recent data</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to identify equipment without recent data so I can detect monitoring interruptions.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Equipment has no recent data</b><br>
    <b>Given</b> that registered equipment has not provided recent monitoring data<br>
    <b>When</b> the system evaluates its available readings<br>
    <b>Then</b> the equipment is identified as having no recent data.<br><br>
    <b>Scenario 2: Equipment has recent data</b><br>
    <b>Given</b> that registered equipment has recent monitoring data<br>
    <b>When</b> the system evaluates its available readings<br>
    <b>Then</b> the equipment is not identified as having missing recent data.
  </td></tr>
</table>

##### **US16 - Automatic data collection**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US16</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP02</td></tr>
  <tr><th>Title</th><td colspan="3">Automatic data collection</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want monitoring data to be collected automatically so I do not have to record it manually.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Monitoring data is received</b><br>
    <b>Given</b> that monitored equipment is providing data<br>
    <b>When</b> the system receives a new reading<br>
    <b>Then</b> the reading is recorded automatically.<br><br>
    <b>Scenario 2: Monitoring data is not received</b><br>
    <b>Given</b> that monitored equipment does not provide data<br>
    <b>When</b> the system expects a monitoring reading<br>
    <b>Then</b> the system identifies that new data was not received.
  </td></tr>
</table>

##### **US17 - View data on mobile**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US17</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP02</td></tr>
  <tr><th>Title</th><td colspan="3">View data on mobile</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to view monitoring data on a mobile device so I can access monitoring information from the mobile application.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Monitoring data is available</b><br>
    <b>Given</b> that the user has access to SafeLab and monitoring data is available<br>
    <b>When</b> the user requests monitoring information from the mobile application<br>
    <b>Then</b> the system provides the available monitoring data.<br><br>
    <b>Scenario 2: Monitoring data cannot be obtained</b><br>
    <b>Given</b> that monitoring data is unavailable<br>
    <b>When</b> the user requests the monitoring information<br>
    <b>Then</b> the system indicates that the requested data cannot be obtained.
  </td></tr>
</table>

##### **US18 - Receive temperature alerts**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US18</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP03</td></tr>
  <tr><th>Title</th><td colspan="3">Receive temperature alerts</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to receive alerts when temperature exceeds established limits so I can respond to the deviation.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Temperature exceeds an established limit</b><br>
    <b>Given</b> that a temperature limit has been defined<br>
    <b>When</b> a recorded temperature exceeds that limit<br>
    <b>Then</b> the system generates a temperature alert.<br><br>
    <b>Scenario 2: Temperature remains within established limits</b><br>
    <b>Given</b> that a temperature limit has been defined<br>
    <b>When</b> a recorded temperature remains within the established limits<br>
    <b>Then</b> the system does not generate a temperature deviation alert.
  </td></tr>
</table>

##### **US19 - Receive humidity alerts**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US19</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP03</td></tr>
  <tr><th>Title</th><td colspan="3">Receive humidity alerts</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to receive alerts when humidity exceeds established limits so I can respond to the deviation.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Humidity exceeds an established limit</b><br>
    <b>Given</b> that a humidity limit has been defined<br>
    <b>When</b> a recorded humidity value exceeds that limit<br>
    <b>Then</b> the system generates a humidity alert.<br><br>
    <b>Scenario 2: Humidity remains within established limits</b><br>
    <b>Given</b> that a humidity limit has been defined<br>
    <b>When</b> a recorded humidity value remains within the established limits<br>
    <b>Then</b> the system does not generate a humidity deviation alert.
  </td></tr>
</table>

##### **US20 - View alerts list**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US20</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP03</td></tr>
  <tr><th>Title</th><td colspan="3">View alerts list</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to view generated alerts so I can manage detected incidents.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Alerts exist</b><br>
    <b>Given</b> that alerts have been generated<br>
    <b>When</b> the user requests the alert information<br>
    <b>Then</b> the system provides the available alerts.<br><br>
    <b>Scenario 2: No alerts exist</b><br>
    <b>Given</b> that no alerts have been generated<br>
    <b>When</b> the user requests the alert information<br>
    <b>Then</b> the system indicates that no alerts are available.
  </td></tr>
</table>
##### **US21 - View alert details**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US21</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP03</td></tr>
  <tr><th>Title</th><td colspan="3">View alert details</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to view alert details so I can understand the detected issue.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Alert exists</b><br>
    <b>Given</b> that a generated alert exists<br>
    <b>When</b> the user requests its details<br>
    <b>Then</b> the system provides the related equipment, recorded value, and time information.<br><br>
    <b>Scenario 2: Alert does not exist</b><br>
    <b>Given</b> that the requested alert is unavailable<br>
    <b>When</b> its details are requested<br>
    <b>Then</b> the system indicates that the alert cannot be found.
  </td></tr>
</table>

##### **US22 - Acknowledge alert**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US22</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP03</td></tr>
  <tr><th>Title</th><td colspan="3">Acknowledge alert</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to acknowledge an alert so I can keep track of alerts that have already been handled.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Active alert is acknowledged</b><br>
    <b>Given</b> that an alert has not been acknowledged<br>
    <b>When</b> the user acknowledges the alert<br>
    <b>Then</b> the system records its acknowledged status.<br><br>
    <b>Scenario 2: Alert is already acknowledged</b><br>
    <b>Given</b> that an alert has already been acknowledged<br>
    <b>When</b> its acknowledgment is requested again<br>
    <b>Then</b> the system preserves its acknowledged status.
  </td></tr>
</table>

##### **US23 - View alerts sorted by severity**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US23</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>Medium</td><th>Epic</th><td>EP03</td></tr>
  <tr><th>Title</th><td colspan="3">View alerts sorted by severity</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to view alerts according to their severity so I can prioritize them.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Alerts with different severity levels exist</b><br>
    <b>Given</b> that multiple alerts with different severity levels are available<br>
    <b>When</b> the user requests alerts ordered by severity<br>
    <b>Then</b> the system provides the alerts according to their severity.<br><br>
    <b>Scenario 2: Alerts have the same severity</b><br>
    <b>Given</b> that available alerts have the same severity<br>
    <b>When</b> the user requests them ordered by severity<br>
    <b>Then</b> the system provides those alerts without changing their severity classification.
  </td></tr>
</table>

##### **US24 - Receive alerts on mobile device**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US24</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP03</td></tr>
  <tr><th>Title</th><td colspan="3">Receive alerts on mobile device</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to receive SafeLab alerts on a mobile device so I can become aware of detected incidents.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: An alert requires mobile notification</b><br>
    <b>Given</b> that the system generates an alert that must be communicated to the user<br>
    <b>When</b> the notification process is executed<br>
    <b>Then</b> the alert information is sent to the registered mobile device.<br><br>
    <b>Scenario 2: Delivery cannot be completed</b><br>
    <b>Given</b> that the alert information cannot be delivered to the device<br>
    <b>When</b> the notification process is executed<br>
    <b>Then</b> the system preserves the generated alert information.
  </td></tr>
</table>

##### **US25 - Set alert limits per equipment**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US25</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP03</td></tr>
  <tr><th>Title</th><td colspan="3">Set alert limits per equipment</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to define temperature and humidity limits for monitored equipment so alerts can be generated when those limits are exceeded.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Valid limits are provided</b><br>
    <b>Given</b> that valid environmental limits are provided for registered equipment<br>
    <b>When</b> the user saves the limits<br>
    <b>Then</b> the system stores the configured limits for that equipment.<br><br>
    <b>Scenario 2: Invalid limits are provided</b><br>
    <b>Given</b> that the provided limits are invalid or incomplete<br>
    <b>When</b> the user attempts to save them<br>
    <b>Then</b> the system rejects the configuration.
  </td></tr>
</table>

##### **US26 - Share alerts with team**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US26</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>Medium</td><th>Epic</th><td>EP03</td></tr>
  <tr><th>Title</th><td colspan="3">Share alerts with team</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want alerts to be available to the team so monitoring incidents can be coordinated.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Alert is available</b><br>
    <b>Given</b> that an alert has been generated<br>
    <b>When</b> authorized team members request the alert information<br>
    <b>Then</b> the system provides the same registered alert information.<br><br>
    <b>Scenario 2: Alert is unavailable</b><br>
    <b>Given</b> that the requested alert does not exist<br>
    <b>When</b> a team member requests its information<br>
    <b>Then</b> the system indicates that the alert is unavailable.
  </td></tr>
</table>

##### **US27 - View historical data**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US27</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP04</td></tr>
  <tr><th>Title</th><td colspan="3">View historical data</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to view historical monitoring data so I can analyze past conditions.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Historical data exists</b><br>
    <b>Given</b> that historical monitoring data is stored for equipment<br>
    <b>When</b> the user requests its history<br>
    <b>Then</b> the system provides the available historical data.<br><br>
    <b>Scenario 2: Historical data does not exist</b><br>
    <b>Given</b> that no historical monitoring data is stored for the requested equipment<br>
    <b>When</b> the user requests its history<br>
    <b>Then</b> the system indicates that no historical data is available.
  </td></tr>
</table>

##### **US28 - Select date range for data**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US28</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>Medium</td><th>Epic</th><td>EP04</td></tr>
  <tr><th>Title</th><td colspan="3">Select date range for data</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to select a date range so I can review monitoring information for a specific period.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Valid date range is provided</b><br>
    <b>Given</b> that a valid start and end date are provided<br>
    <b>When</b> the user requests monitoring data for that range<br>
    <b>Then</b> the system provides data corresponding to the selected period.<br><br>
    <b>Scenario 2: Invalid date range is provided</b><br>
    <b>Given</b> that the provided date range is invalid<br>
    <b>When</b> monitoring data is requested<br>
    <b>Then</b> the system rejects the date range.
  </td></tr>
</table>

##### **US29 - Compare data between periods**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US29</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>Medium</td><th>Epic</th><td>EP04</td></tr>
  <tr><th>Title</th><td colspan="3">Compare data between periods</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to compare monitoring data between periods so I can identify variations.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Both periods contain data</b><br>
    <b>Given</b> that two valid periods with monitoring data are provided<br>
    <b>When</b> the user requests the comparison<br>
    <b>Then</b> the system provides monitoring information for both periods.<br><br>
    <b>Scenario 2: Required comparison information is incomplete</b><br>
    <b>Given</b> that the required periods are not completely defined<br>
    <b>When</b> the user requests the comparison<br>
    <b>Then</b> the system rejects the comparison request.
  </td></tr>
</table>

##### **US30 - Generate report by equipment and date**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US30</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP04</td></tr>
  <tr><th>Title</th><td colspan="3">Generate report by equipment and date</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to generate reports by equipment and date so I can use monitoring records for control and auditing.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Required report information is available</b><br>
    <b>Given</b> that valid equipment and date information are provided<br>
    <b>When</b> the user requests a report<br>
    <b>Then</b> the system generates a report using the available monitoring information.<br><br>
    <b>Scenario 2: Required information is incomplete</b><br>
    <b>Given</b> that required report information is missing<br>
    <b>When</b> the user requests a report<br>
    <b>Then</b> the system rejects the report request.
  </td></tr>
</table>

##### **US31 - Download report file**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US31</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP04</td></tr>
  <tr><th>Title</th><td colspan="3">Download report file</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to download generated reports so I can use or share them outside SafeLab.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Generated report exists</b><br>
    <b>Given</b> that a report has been generated<br>
    <b>When</b> the user requests its download<br>
    <b>Then</b> the system provides the generated report file.<br><br>
    <b>Scenario 2: Generated report does not exist</b><br>
    <b>Given</b> that no generated report is available<br>
    <b>When</b> the user requests a report download<br>
    <b>Then</b> the system indicates that no report is available.
  </td></tr>
</table>

##### **US32 - View incident history**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US32</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP04</td></tr>
  <tr><th>Title</th><td colspan="3">View incident history</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to view incident history so I can review previous alerts and events.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Incident history exists</b><br>
    <b>Given</b> that previous alerts or incidents have been recorded<br>
    <b>When</b> the user requests incident history<br>
    <b>Then</b> the system provides the available historical incident information.<br><br>
    <b>Scenario 2: Incident history does not exist</b><br>
    <b>Given</b> that no previous alerts or incidents have been recorded<br>
    <b>When</b> the user requests incident history<br>
    <b>Then</b> the system indicates that no incident history is available.
  </td></tr>
</table>

##### **US33 - Export data file**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US33</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>Medium</td><th>Epic</th><td>EP04</td></tr>
  <tr><th>Title</th><td colspan="3">Export data file</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to export monitoring data so I can use it outside the system.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Data is available</b><br>
    <b>Given</b> that monitoring data is available for export<br>
    <b>When</b> the user requests the export<br>
    <b>Then</b> the system generates an export file using the available data.<br><br>
    <b>Scenario 2: Data is unavailable</b><br>
    <b>Given</b> that no monitoring data is available for export<br>
    <b>When</b> the user requests the export<br>
    <b>Then</b> the system indicates that no data is available.
  </td></tr>
</table>

##### **US34 - Compare weekly and monthly data**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US34</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>Medium</td><th>Epic</th><td>EP04</td></tr>
  <tr><th>Title</th><td colspan="3">Compare weekly and monthly data</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to compare weekly and monthly monitoring data so I can identify variations between periods.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Weekly and monthly data are available</b><br>
    <b>Given</b> that monitoring information exists for the selected week and month<br>
    <b>When</b> the user requests the comparison<br>
    <b>Then</b> the system provides the information corresponding to both periods.<br><br>
    <b>Scenario 2: Required period information is incomplete</b><br>
    <b>Given</b> that the week or month has not been completely defined<br>
    <b>When</b> the user requests the comparison<br>
    <b>Then</b> the system rejects the comparison request.
  </td></tr>
</table>

##### **US35 - View equipment condition**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US35</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP05</td></tr>
  <tr><th>Title</th><td colspan="3">View equipment condition</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to view equipment condition so I can identify possible failures.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Equipment operates normally</b><br>
    <b>Given</b> that the equipment operates under its expected conditions<br>
    <b>When</b> the user requests its condition<br>
    <b>Then</b> the system identifies its condition as normal.<br><br>
    <b>Scenario 2: An abnormal condition is detected</b><br>
    <b>Given</b> that an abnormal equipment condition has been detected<br>
    <b>When</b> the user requests its condition<br>
    <b>Then</b> the system identifies the detected abnormal condition.
  </td></tr>
</table>

##### **US36 - View abnormal values**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US36</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP05</td></tr>
  <tr><th>Title</th><td colspan="3">View abnormal values</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to identify environmental values outside established limits so I can detect problems.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Value exceeds established limits</b><br>
    <b>Given</b> that environmental limits are defined<br>
    <b>When</b> a recorded value is outside those limits<br>
    <b>Then</b> the system identifies the value as abnormal.<br><br>
    <b>Scenario 2: Value remains within limits</b><br>
    <b>Given</b> that environmental limits are defined<br>
    <b>When</b> a recorded value remains within those limits<br>
    <b>Then</b> the system does not identify the value as abnormal.
  </td></tr>
</table>

##### **US37 - Receive equipment warning alerts**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US37</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP05</td></tr>
  <tr><th>Title</th><td colspan="3">Receive equipment warning alerts</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to receive equipment warnings so I can identify possible failures.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Abnormal equipment condition is detected</b><br>
    <b>Given</b> that the system detects an abnormal equipment condition<br>
    <b>When</b> the condition meets the criteria for a warning<br>
    <b>Then</b> the system generates an equipment warning.<br><br>
    <b>Scenario 2: Equipment operates normally</b><br>
    <b>Given</b> that no abnormal equipment condition is detected<br>
    <b>When</b> the equipment is monitored<br>
    <b>Then</b> the system does not generate an equipment warning.
  </td></tr>
</table>

##### **US38 - View equipment performance data**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US38</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>Medium</td><th>Epic</th><td>EP05</td></tr>
  <tr><th>Title</th><td colspan="3">View equipment performance data</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to view equipment performance over time so I can evaluate its operation.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Performance data exists</b><br>
    <b>Given</b> that historical equipment data is available<br>
    <b>When</b> the user requests equipment performance information<br>
    <b>Then</b> the system provides the available performance data.<br><br>
    <b>Scenario 2: Performance data does not exist</b><br>
    <b>Given</b> that no performance data is available<br>
    <b>When</b> the user requests equipment performance information<br>
    <b>Then</b> the system indicates that no performance data is available.
  </td></tr>
</table>

##### **US39 - View equipment usage data**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US39</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>Medium</td><th>Epic</th><td>EP05</td></tr>
  <tr><th>Title</th><td colspan="3">View equipment usage data</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to view equipment usage data so I can manage monitored resources.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Usage data exists</b><br>
    <b>Given</b> that equipment usage data is available<br>
    <b>When</b> the user requests usage information<br>
    <b>Then</b> the system provides the available usage data.<br><br>
    <b>Scenario 2: Usage data does not exist</b><br>
    <b>Given</b> that no usage data is available<br>
    <b>When</b> the user requests usage information<br>
    <b>Then</b> the system indicates that no usage data is available.
  </td></tr>
</table>

##### **US40 - Register maintenance record**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US40</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP05</td></tr>
  <tr><th>Title</th><td colspan="3">Register maintenance record</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to register equipment maintenance information so I can keep its maintenance history.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Valid maintenance information is provided</b><br>
    <b>Given</b> that valid maintenance information is provided for registered equipment<br>
    <b>When</b> the user registers the maintenance record<br>
    <b>Then</b> the system stores the maintenance information.<br><br>
    <b>Scenario 2: Maintenance information is incomplete</b><br>
    <b>Given</b> that required maintenance information is missing<br>
    <b>When</b> the user attempts to register the maintenance record<br>
    <b>Then</b> the system rejects the registration.
  </td></tr>
</table>
##### **US41 - View maintenance history**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US41</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP05</td></tr>
  <tr><th>Title</th><td colspan="3">View maintenance history</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to view equipment maintenance history so I can review previous maintenance records.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Maintenance records exist</b><br>
    <b>Given</b> that maintenance records have been registered for equipment<br>
    <b>When</b> the user requests its maintenance history<br>
    <b>Then</b> the system provides the available maintenance records.<br><br>
    <b>Scenario 2: Maintenance records do not exist</b><br>
    <b>Given</b> that no maintenance records have been registered<br>
    <b>When</b> the user requests the maintenance history<br>
    <b>Then</b> the system indicates that no maintenance records are available.
  </td></tr>
</table>

##### **US42 - View equipment reliability**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US42</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP05</td></tr>
  <tr><th>Title</th><td colspan="3">View equipment reliability</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to view equipment stability over time so I can evaluate its reliability.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Historical equipment data exists</b><br>
    <b>Given</b> that historical equipment data is available<br>
    <b>When</b> the user requests reliability information<br>
    <b>Then</b> the system provides the available stability information over time.<br><br>
    <b>Scenario 2: Historical equipment data does not exist</b><br>
    <b>Given</b> that no historical equipment data is available<br>
    <b>When</b> the user requests reliability information<br>
    <b>Then</b> the system indicates that reliability information is unavailable.
  </td></tr>
</table>

##### **US43 - View dashboard**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US43</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP06</td></tr>
  <tr><th>Title</th><td colspan="3">View dashboard</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to view key SafeLab information so I can understand the current monitoring status.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: System information is available</b><br>
    <b>Given</b> that SafeLab contains monitoring information<br>
    <b>When</b> the user requests the system overview<br>
    <b>Then</b> the system provides the available key monitoring information.<br><br>
    <b>Scenario 2: System information is unavailable</b><br>
    <b>Given</b> that no monitoring information is currently available<br>
    <b>When</b> the user requests the system overview<br>
    <b>Then</b> the system indicates that no monitoring information is available.
  </td></tr>
</table>

##### **US44 - View critical alerts**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US44</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP06</td></tr>
  <tr><th>Title</th><td colspan="3">View critical alerts</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to view critical alerts so I can prioritize situations requiring attention.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Critical alerts exist</b><br>
    <b>Given</b> that alerts classified as critical are available<br>
    <b>When</b> the user requests critical alerts<br>
    <b>Then</b> the system provides the available critical alerts.<br><br>
    <b>Scenario 2: No critical alerts exist</b><br>
    <b>Given</b> that no alerts are classified as critical<br>
    <b>When</b> the user requests critical alerts<br>
    <b>Then</b> the system indicates that no critical alerts are available.
  </td></tr>
</table>

##### **US45 - View summary with totals**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US45</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP06</td></tr>
  <tr><th>Title</th><td colspan="3">View summary with totals</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to view a summary of equipment and alerts so I can obtain an overview of the monitored environment.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Summary information exists</b><br>
    <b>Given</b> that equipment or alert information is available<br>
    <b>When</b> the user requests the monitoring summary<br>
    <b>Then</b> the system provides the available totals.<br><br>
    <b>Scenario 2: Summary information does not exist</b><br>
    <b>Given</b> that no equipment or alert information is available<br>
    <b>When</b> the user requests the monitoring summary<br>
    <b>Then</b> the system indicates that summary information is unavailable.
  </td></tr>
</table>

##### **US46 - View equipment with active alerts**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US46</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP06</td></tr>
  <tr><th>Title</th><td colspan="3">View equipment with active alerts</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to identify equipment with active alerts so I can focus on equipment with detected issues.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Equipment has active alerts</b><br>
    <b>Given</b> that registered equipment has active alerts<br>
    <b>When</b> the user requests equipment with active alerts<br>
    <b>Then</b> the system provides the corresponding equipment.<br><br>
    <b>Scenario 2: No equipment has active alerts</b><br>
    <b>Given</b> that no registered equipment has active alerts<br>
    <b>When</b> the user requests equipment with active alerts<br>
    <b>Then</b> the system indicates that no affected equipment is available.
  </td></tr>
</table>

##### **US48 - View alert trends**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US48</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>Medium</td><th>Epic</th><td>EP06</td></tr>
  <tr><th>Title</th><td colspan="3">View alert trends</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to view alert trends so I can analyze alert behavior over time.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Alert history exists</b><br>
    <b>Given</b> that historical alert information is available<br>
    <b>When</b> the user requests alert trends<br>
    <b>Then</b> the system provides trend information using the available alert history.<br><br>
    <b>Scenario 2: Alert history does not exist</b><br>
    <b>Given</b> that no historical alert information is available<br>
    <b>When</b> the user requests alert trends<br>
    <b>Then</b> the system indicates that trend information is unavailable.
  </td></tr>
</table>

##### **US49 - View temperature trends**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US49</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>Medium</td><th>Epic</th><td>EP06</td></tr>
  <tr><th>Title</th><td colspan="3">View temperature trends</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to view temperature trends so I can analyze temperature changes over time.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Temperature history exists</b><br>
    <b>Given</b> that historical temperature data is available<br>
    <b>When</b> the user requests temperature trends<br>
    <b>Then</b> the system provides trend information using the available historical data.<br><br>
    <b>Scenario 2: Temperature history does not exist</b><br>
    <b>Given</b> that historical temperature data is unavailable<br>
    <b>When</b> the user requests temperature trends<br>
    <b>Then</b> the system indicates that temperature trend information is unavailable.
  </td></tr>
</table>

##### **US50 - View humidity trends**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US50</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>Medium</td><th>Epic</th><td>EP06</td></tr>
  <tr><th>Title</th><td colspan="3">View humidity trends</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to view humidity trends so I can analyze humidity changes over time.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Humidity history exists</b><br>
    <b>Given</b> that historical humidity data is available<br>
    <b>When</b> the user requests humidity trends<br>
    <b>Then</b> the system provides trend information using the available historical data.<br><br>
    <b>Scenario 2: Humidity history does not exist</b><br>
    <b>Given</b> that historical humidity data is unavailable<br>
    <b>When</b> the user requests humidity trends<br>
    <b>Then</b> the system indicates that humidity trend information is unavailable.
  </td></tr>
</table>

##### **US51 - Login with Google account**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US51</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP07</td></tr>
  <tr><th>Title</th><td colspan="3">Login with Google account</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to log in using a Google account so I can access SafeLab.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Authentication is successful</b><br>
    <b>Given</b> that valid Google authentication information is provided<br>
    <b>When</b> the user requests access to SafeLab<br>
    <b>Then</b> the system grants access to the corresponding account.<br><br>
    <b>Scenario 2: Authentication is unsuccessful</b><br>
    <b>Given</b> that Google authentication cannot be validated<br>
    <b>When</b> the user requests access to SafeLab<br>
    <b>Then</b> the system does not grant access.
  </td></tr>
</table>

##### **US52 - Login with email and password**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US52</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP07</td></tr>
  <tr><th>Title</th><td colspan="3">Login with email and password</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to log in using email and password so I can access my SafeLab account.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Credentials are valid</b><br>
    <b>Given</b> that valid account credentials are provided<br>
    <b>When</b> the user requests access<br>
    <b>Then</b> the system grants access to the corresponding account.<br><br>
    <b>Scenario 2: Credentials are invalid</b><br>
    <b>Given</b> that invalid account credentials are provided<br>
    <b>When</b> the user requests access<br>
    <b>Then</b> the system does not grant access.
  </td></tr>
</table>

##### **US53 - Recover password by email**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US53</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>Medium</td><th>Epic</th><td>EP07</td></tr>
  <tr><th>Title</th><td colspan="3">Recover password by email</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to recover account access through email so I can regain access when I cannot use my password.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Registered email is provided</b><br>
    <b>Given</b> that the provided email belongs to a registered account<br>
    <b>When</b> the user requests password recovery<br>
    <b>Then</b> the system initiates the password recovery process for that email.<br><br>
    <b>Scenario 2: Unregistered email is provided</b><br>
    <b>Given</b> that the provided email does not belong to a registered account<br>
    <b>When</b> password recovery is requested<br>
    <b>Then</b> the system does not initiate recovery for an account that does not exist.
  </td></tr>
</table>

##### **US54 - Logout from system**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US54</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP07</td></tr>
  <tr><th>Title</th><td colspan="3">Logout from system</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to log out so I can end my SafeLab session.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Active session exists</b><br>
    <b>Given</b> that the user has an active session<br>
    <b>When</b> the user requests to log out<br>
    <b>Then</b> the system ends the active session.<br><br>
    <b>Scenario 2: Session is no longer active</b><br>
    <b>Given</b> that the user session has already expired<br>
    <b>When</b> access to protected information is requested<br>
    <b>Then</b> the system requires authentication again.
  </td></tr>
</table>

##### **US55 - Assign user role**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US55</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP07</td></tr>
  <tr><th>Title</th><td colspan="3">Assign user role</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company with user management responsibility, I want to assign roles so registered users have the corresponding access.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Registered user exists</b><br>
    <b>Given</b> that a registered user exists<br>
    <b>When</b> an authorized user assigns a valid role<br>
    <b>Then</b> the system associates the role with that user.<br><br>
    <b>Scenario 2: Requested user does not exist</b><br>
    <b>Given</b> that the requested user is not registered<br>
    <b>When</b> a role assignment is requested<br>
    <b>Then</b> the system rejects the assignment.
  </td></tr>
</table>

##### **US56 - View SafeLab Landing Page**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US56</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP08</td></tr>
  <tr><th>Title</th><td colspan="3">View SafeLab Landing Page</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to access the SafeLab Landing Page so I can learn about the product.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Landing Page is available</b><br>
    <b>Given</b> that the SafeLab Landing Page is publicly available<br>
    <b>When</b> a visitor accesses it<br>
    <b>Then</b> the site provides the available SafeLab product information.<br><br>
    <b>Scenario 2: Requested Landing Page resource is unavailable</b><br>
    <b>Given</b> that a requested Landing Page resource cannot be obtained<br>
    <b>When</b> the visitor accesses that resource<br>
    <b>Then</b> the site does not present invalid content as available information.
  </td></tr>
</table>

##### **US57 - Change Landing Page language**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US57</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>Medium</td><th>Epic</th><td>EP08</td></tr>
  <tr><th>Title</th><td colspan="3">Change Landing Page language</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to access Landing Page content in the supported languages so I can understand the presented information.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Supported language is selected</b><br>
    <b>Given</b> that the Landing Page supports English (en_US) and Latin American Spanish (es_419)<br>
    <b>When</b> the visitor selects a supported language<br>
    <b>Then</b> the available Landing Page content is provided in the selected language.<br><br>
    <b>Scenario 2: No alternative language is selected</b><br>
    <b>Given</b> that the visitor has not selected another supported language<br>
    <b>When</b> the Landing Page is accessed<br>
    <b>Then</b> the content is provided in English (en_US), the default language.
  </td></tr>
</table>

##### **US58 - Access Terms and Conditions**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US58</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>Medium</td><th>Epic</th><td>EP08</td></tr>
  <tr><th>Title</th><td colspan="3">Access Terms and Conditions</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to access SafeLab's Terms and Conditions so I can review the conditions associated with the service.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Terms and Conditions are requested from the Landing Page</b><br>
    <b>Given</b> that SafeLab Terms and Conditions are available<br>
    <b>When</b> a visitor requests them from the Landing Page<br>
    <b>Then</b> the site provides the Terms and Conditions.<br><br>
    <b>Scenario 2: Terms and Conditions are requested during account registration</b><br>
    <b>Given</b> that a user is registering a SafeLab account<br>
    <b>When</b> the Terms and Conditions are requested<br>
    <b>Then</b> the application provides access to the Terms and Conditions.
  </td></tr>
</table>

##### **US59 - Register user account**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US59</td><th>User</th><td>Hospital Laboratory Staff / Pharmaceutical Company</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP07</td></tr>
  <tr><th>Title</th><td colspan="3">Register user account</td></tr>
  <tr><th>Description</th><td colspan="3">As a Hospital Laboratory Staff member or Pharmaceutical Company, I want to register a SafeLab account so I can access the service.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Valid registration information is provided</b><br>
    <b>Given</b> that the required account information is valid<br>
    <b>When</b> the user requests account registration<br>
    <b>Then</b> the system creates the account.<br><br>
    <b>Scenario 2: Required registration information is invalid or incomplete</b><br>
    <b>Given</b> that required account information is invalid or incomplete<br>
    <b>When</b> the user requests account registration<br>
    <b>Then</b> the system rejects the account registration.
  </td></tr>
</table>

<br>

##### **US60 - Provide monitoring organization services**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US60</td><th>User</th><td>Developer</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP01</td></tr>
  <tr><th>Title</th><td colspan="3">Provide monitoring organization services</td></tr>
  <tr><th>Description</th><td colspan="3">As a Developer, I want the RESTful API to provide operations for monitoring sites, storage areas, and equipment so SafeLab applications can use the corresponding organization information.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Valid request is received</b><br>
    <b>Given</b> that a valid request for supported monitoring organization data is received<br>
    <b>When</b> the RESTful service processes the request<br>
    <b>Then</b> the service returns the corresponding successful response.<br><br>
    <b>Scenario 2: Requested resource does not exist</b><br>
    <b>Given</b> that the requested monitoring organization resource does not exist<br>
    <b>When</b> the RESTful service processes the request<br>
    <b>Then</b> the service returns a response indicating that the resource was not found.
  </td></tr>
</table>

##### **US61 - Provide environmental monitoring services**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US61</td><th>User</th><td>Developer</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP02</td></tr>
  <tr><th>Title</th><td colspan="3">Provide environmental monitoring services</td></tr>
  <tr><th>Description</th><td colspan="3">As a Developer, I want the RESTful API to provide environmental monitoring data so SafeLab applications can consume temperature, humidity, and equipment status information.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Monitoring data exists</b><br>
    <b>Given</b> that monitoring information is available for the requested equipment<br>
    <b>When</b> a valid request is processed<br>
    <b>Then</b> the service returns the available monitoring information.<br><br>
    <b>Scenario 2: Requested equipment does not exist</b><br>
    <b>Given</b> that the requested equipment is not registered<br>
    <b>When</b> a monitoring request is processed<br>
    <b>Then</b> the service returns a response indicating that the equipment was not found.
  </td></tr>
</table>

##### **US62 - Provide alert and incident services**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US62</td><th>User</th><td>Developer</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP03</td></tr>
  <tr><th>Title</th><td colspan="3">Provide alert and incident services</td></tr>
  <tr><th>Description</th><td colspan="3">As a Developer, I want the RESTful API to provide alert and incident information so SafeLab applications can use generated alerts and their status.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Valid alert request is received</b><br>
    <b>Given</b> that the requested alert information exists<br>
    <b>When</b> the RESTful service processes a valid request<br>
    <b>Then</b> the service returns the corresponding alert information.<br><br>
    <b>Scenario 2: Requested alert does not exist</b><br>
    <b>Given</b> that the requested alert is unavailable<br>
    <b>When</b> the RESTful service processes the request<br>
    <b>Then</b> the service returns a response indicating that the alert was not found.
  </td></tr>
</table>

##### **US63 - Provide historical data and report services**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US63</td><th>User</th><td>Developer</td></tr>
  <tr><th>Priority</th><td>Medium</td><th>Epic</th><td>EP04</td></tr>
  <tr><th>Title</th><td colspan="3">Provide historical data and report services</td></tr>
  <tr><th>Description</th><td colspan="3">As a Developer, I want the RESTful API to provide historical monitoring data and report information so SafeLab applications can support analysis and reporting features.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Requested historical information exists</b><br>
    <b>Given</b> that historical monitoring information exists for a valid request<br>
    <b>When</b> the RESTful service processes the request<br>
    <b>Then</b> the service returns the available historical information.<br><br>
    <b>Scenario 2: Historical information is unavailable</b><br>
    <b>Given</b> that no information exists for the requested criteria<br>
    <b>When</b> the RESTful service processes the request<br>
    <b>Then</b> the service returns a response indicating that no corresponding information is available.
  </td></tr>
</table>

##### **US64 - Provide user access services**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US64</td><th>User</th><td>Developer</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP07</td></tr>
  <tr><th>Title</th><td colspan="3">Provide user access services</td></tr>
  <tr><th>Description</th><td colspan="3">As a Developer, I want the RESTful API to support SafeLab account and access operations so the mobile applications can use the required user access capabilities.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Valid access request is received</b><br>
    <b>Given</b> that valid account information is provided<br>
    <b>When</b> the RESTful service processes a supported access request<br>
    <b>Then</b> the service returns the corresponding successful response.<br><br>
    <b>Scenario 2: Invalid account information is provided</b><br>
    <b>Given</b> that the provided account information cannot be validated<br>
    <b>When</b> the RESTful service processes the request<br>
    <b>Then</b> the service returns a response indicating that the operation cannot be completed.
  </td></tr>
</table>

##### **US65 - Support local data storage on mobile device**

<table style="width: 100%; border-collapse: collapse;">
  <tr><th>Story ID</th><td>US65</td><th>User</th><td>Developer</td></tr>
  <tr><th>Priority</th><td>High</td><th>Epic</th><td>EP02</td></tr>
  <tr><th>Title</th><td colspan="3">Support local data storage on mobile device</td></tr>
  <tr><th>Description</th><td colspan="3">As a Developer, I want the mobile application to support local storage of selected SafeLab information so SafeLab can persist and retrieve monitoring information on the device.</td></tr>
  <tr><th>Acceptance Criteria</th><td colspan="3">
    <b>Scenario 1: Information is selected for local persistence</b><br>
    <b>Given</b> that SafeLab information has been defined for local storage<br>
    <b>When</b> the mobile application stores that information<br>
    <b>Then</b> the information remains persisted on the device according to the defined storage behavior.<br><br>
    <b>Scenario 2: Stored information is requested</b><br>
    <b>Given</b> that selected SafeLab information has been stored locally<br>
    <b>When</b> the mobile application requests the stored information<br>
    <b>Then</b> the locally persisted information can be retrieved.
  </td></tr>
</table>

<br>

#### **Spike Stories**

##### **SP01 - Investigate Google Authentication Integration Options**

<p style="text-align: justify;">
  <b>Context:</b> SafeLab includes Google account login through US51 - Login with Google account. The mobile solution includes native and cross-platform applications that interact with internally developed RESTful services. Before developing the complete authentication flow, the development team needs to evaluate the integration approach, mobile compatibility, backend requirements, and technical considerations required to validate authenticated users.
</p>

<p style="text-align: justify;">
  <b>Spike Story:</b><br>
  As a Development Team,<br>
  I want to investigate and prototype the integration of Google account authentication in the SafeLab mobile applications and RESTful services,<br>
  so we can understand the technical requirements, dependencies, risks, and effort required before implementing US51 - Login with Google account.
</p>

<p style="text-align: justify;">
  <b>Acceptance Criteria:</b>
</p>

<p style="text-align: justify;">
  <b>Scenario 1: Official authentication documentation is reviewed</b><br>
  <b>Given</b> that SafeLab requires users to authenticate using a Google account<br>
  <b>When</b> the developer reviews the official documentation related to Google authentication<br>
  <b>Then</b> the authentication flow, required configurations, and main integration requirements are documented.
</p>

<p style="text-align: justify;">
  <b>Scenario 2: Native mobile compatibility is evaluated</b><br>
  <b>Given</b> that SafeLab must include a native mobile application<br>
  <b>When</b> the developer evaluates the authentication integration for the native mobile implementation<br>
  <b>Then</b> the required configuration, dependencies, and authentication flow are documented.
</p>

<p style="text-align: justify;">
  <b>Scenario 3: Cross-platform compatibility is evaluated</b><br>
  <b>Given</b> that SafeLab must also include a cross-platform mobile application<br>
  <b>When</b> the developer evaluates the authentication integration for the cross-platform implementation<br>
  <b>Then</b> the compatibility requirements and identified integration differences are documented.
</p>

<p style="text-align: justify;">
  <b>Scenario 4: Backend authentication requirements are evaluated</b><br>
  <b>Given</b> that SafeLab uses internally developed RESTful services<br>
  <b>When</b> the developer analyzes how authenticated user information must be validated by the backend<br>
  <b>Then</b> the required interaction between the mobile application and the RESTful services is documented.
</p>

<p style="text-align: justify;">
  <b>Scenario 5: Security considerations are identified</b><br>
  <b>Given</b> that authentication provides access to SafeLab user information and functionalities<br>
  <b>When</b> the developer analyzes the authentication flow<br>
  <b>Then</b> the main security considerations and required validation steps are documented.
</p>

<p style="text-align: justify;">
  <b>Scenario 6: Authentication integration is prototyped</b><br>
  <b>Given</b> that an integration approach has been selected for evaluation<br>
  <b>When</b> the developer creates a minimal proof of concept<br>
  <b>Then</b> the prototype verifies whether a Google account can be authenticated and recognized by SafeLab.
</p>

<p style="text-align: justify;">
  <b>Scenario 7: Implementation effort is estimated</b><br>
  <b>Given</b> that the authentication requirements and dependencies have been identified<br>
  <b>When</b> the development team reviews the work required for the complete implementation<br>
  <b>Then</b> the main implementation tasks and an approximate effort estimation are documented.
</p>

<p style="text-align: justify;">
  <b>Scenario 8: Findings are documented and reviewed</b><br>
  <b>Given</b> that the investigation and technical validation are complete<br>
  <b>When</b> the development team reviews the collected findings<br>
  <b>Then</b> the selected approach, requirements, dependencies, risks, and implementation considerations are documented for the refinement of US51.
</p>

<p style="text-align: justify;">
  <b>Definition of Done:</b><br>
  - Official authentication documentation is reviewed.<br>
  - Native, cross-platform, and backend integration requirements are documented.<br>
  - Security considerations and dependencies are identified.<br>
  - A minimal authentication proof of concept is completed.<br>
  - The implementation effort is estimated.<br>
  - The findings are reviewed by the development team and used to refine US51.
</p>


##### **SP02 - Investigate Local Storage Options for Monitoring Data**

<p style="text-align: justify;">
  <b>Context:</b> SafeLab manages environmental monitoring information such as temperature, humidity, and equipment status and includes local persistence through US65 - Support local data storage on mobile device. Before implementing the complete persistence mechanism, the development team needs to evaluate a suitable local storage approach and verify that SafeLab monitoring information can be stored and retrieved correctly.
</p>

<p style="text-align: justify;">
  <b>Spike Story:</b><br>
  As a Development Team,<br>
  I want to investigate and prototype local storage alternatives for SafeLab monitoring data,<br>
  so we can select an appropriate persistence approach and understand its requirements, limitations, dependencies, and implementation effort before implementing US65 - Support local data storage on mobile device.
</p>

<p style="text-align: justify;">
  <b>Acceptance Criteria:</b>
</p>

<p style="text-align: justify;">
  <b>Scenario 1: Local storage alternatives are investigated</b><br>
  <b>Given</b> that SafeLab must persist selected information locally on the mobile device<br>
  <b>When</b> the developer investigates storage alternatives compatible with the mobile solution<br>
  <b>Then</b> the available alternatives and their main characteristics are documented.
</p>

<p style="text-align: justify;">
  <b>Scenario 2: Native mobile compatibility is evaluated</b><br>
  <b>Given</b> that SafeLab must include a native mobile application<br>
  <b>When</b> the developer evaluates the candidate persistence alternatives<br>
  <b>Then</b> their compatibility and integration requirements for the native implementation are documented.
</p>

<p style="text-align: justify;">
  <b>Scenario 3: Cross-platform compatibility is evaluated</b><br>
  <b>Given</b> that SafeLab must include a cross-platform mobile application<br>
  <b>When</b> the developer evaluates the candidate persistence alternatives<br>
  <b>Then</b> their compatibility and integration requirements for the cross-platform implementation are documented.
</p>

<p style="text-align: justify;">
  <b>Scenario 4: Monitoring information for the prototype is defined</b><br>
  <b>Given</b> that SafeLab manages temperature, humidity, and equipment status information<br>
  <b>When</b> the developer defines the data required for the persistence test<br>
  <b>Then</b> the monitoring information used by the proof of concept is documented.
</p>

<p style="text-align: justify;">
  <b>Scenario 5: Local persistence is prototyped</b><br>
  <b>Given</b> that a candidate storage approach has been selected<br>
  <b>When</b> the developer stores sample SafeLab monitoring information on the device<br>
  <b>Then</b> the prototype verifies that the selected information remains locally persisted.
</p>

<p style="text-align: justify;">
  <b>Scenario 6: Stored monitoring information is retrieved</b><br>
  <b>Given</b> that SafeLab monitoring information has been persisted locally<br>
  <b>When</b> the prototype requests the stored information<br>
  <b>Then</b> the previously stored information can be retrieved correctly.
</p>

<p style="text-align: justify;">
  <b>Scenario 7: Persistence after application restart is evaluated</b><br>
  <b>Given</b> that monitoring information has been stored locally<br>
  <b>When</b> the application is closed and started again<br>
  <b>Then</b> the prototype verifies whether the persisted information remains available.
</p>

<p style="text-align: justify;">
  <b>Scenario 8: Implementation effort and findings are documented</b><br>
  <b>Given</b> that the storage alternatives and proof of concept have been evaluated<br>
  <b>When</b> the development team reviews the results<br>
  <b>Then</b> the selected approach, dependencies, limitations, implementation tasks, and approximate effort are documented for the refinement of US65.
</p>

<p style="text-align: justify;">
  <b>Definition of Done:</b><br>
  - Compatible local storage alternatives are reviewed.<br>
  - Native and cross-platform integration requirements are documented.<br>
  - The monitoring information used for technical validation is identified.<br>
  - A minimal proof of concept stores and retrieves monitoring information locally.<br>
  - Persistence after application restart is validated.<br>
  - The implementation effort is estimated.<br>
  - The findings are reviewed by the development team and used to refine US65.
</p>


##### **SP03 - Investigate Mobile Alert Delivery Options**

<p style="text-align: justify;">
  <b>Context:</b> SafeLab includes alerts related to temperature, humidity, and equipment conditions and mobile alert reception through US24 - Receive alerts on mobile device. Before implementing the complete delivery mechanism, the development team needs to investigate how SafeLab alerts can be communicated to mobile devices and how this process interacts with the mobile applications and the internally developed RESTful services.
</p>

<p style="text-align: justify;">
  <b>Spike Story:</b><br>
  As a Development Team,<br>
  I want to investigate and prototype mobile alert delivery alternatives for SafeLab,<br>
  so we can select an appropriate approach and understand its technical requirements, dependencies, risks, and implementation effort before implementing US24 - Receive alerts on mobile device.
</p>

<p style="text-align: justify;">
  <b>Acceptance Criteria:</b>
</p>

<p style="text-align: justify;">
  <b>Scenario 1: Alert delivery alternatives are investigated</b><br>
  <b>Given</b> that SafeLab needs to communicate generated alerts to mobile users<br>
  <b>When</b> the developer investigates technically viable mobile alert delivery alternatives<br>
  <b>Then</b> the available alternatives and their main integration requirements are documented.
</p>

<p style="text-align: justify;">
  <b>Scenario 2: Native mobile compatibility is evaluated</b><br>
  <b>Given</b> that SafeLab must include a native mobile application<br>
  <b>When</b> the developer evaluates the candidate alert delivery alternatives<br>
  <b>Then</b> their compatibility and configuration requirements for the native mobile application are documented.
</p>

<p style="text-align: justify;">
  <b>Scenario 3: Cross-platform compatibility is evaluated</b><br>
  <b>Given</b> that SafeLab must include a cross-platform mobile application<br>
  <b>When</b> the developer evaluates the candidate alert delivery alternatives<br>
  <b>Then</b> their compatibility and configuration requirements for the cross-platform implementation are documented.
</p>

<p style="text-align: justify;">
  <b>Scenario 4: Integration with SafeLab alerts is analyzed</b><br>
  <b>Given</b> that SafeLab generates alerts from temperature, humidity, and equipment conditions<br>
  <b>When</b> the developer analyzes the mobile alert delivery process<br>
  <b>Then</b> the required interaction between generated alerts, RESTful services, and mobile applications is documented.
</p>

<p style="text-align: justify;">
  <b>Scenario 5: Required dependencies and configuration are identified</b><br>
  <b>Given</b> that mobile alert delivery may require additional configuration or dependencies<br>
  <b>When</b> the developer evaluates the selected alternative<br>
  <b>Then</b> the required dependencies, configuration steps, and identified limitations are documented.
</p>

<p style="text-align: justify;">
  <b>Scenario 6: Alert delivery is prototyped</b><br>
  <b>Given</b> that an alert delivery alternative has been selected for evaluation<br>
  <b>When</b> the developer generates and sends a SafeLab test alert<br>
  <b>Then</b> the proof of concept verifies whether the alert can be delivered to a mobile device.
</p>

<p style="text-align: justify;">
  <b>Scenario 7: Implementation effort is estimated</b><br>
  <b>Given</b> that the technical requirements and dependencies have been identified<br>
  <b>When</b> the development team reviews the work required for mobile alert delivery<br>
  <b>Then</b> the main implementation tasks and an approximate effort estimation are documented.
</p>

<p style="text-align: justify;">
  <b>Scenario 8: Findings are documented and reviewed</b><br>
  <b>Given</b> that the technical evaluation is complete<br>
  <b>When</b> the development team reviews the results<br>
  <b>Then</b> the selected approach, integration requirements, dependencies, limitations, risks, and implementation considerations are documented for the refinement of US24.
</p>

<p style="text-align: justify;">
  <b>Definition of Done:</b><br>
  - Mobile alert delivery alternatives are evaluated.<br>
  - Native and cross-platform compatibility is documented.<br>
  - Integration requirements with SafeLab alerts and RESTful services are identified.<br>
  - A minimal proof of concept using a SafeLab test alert is completed.<br>
  - Technical dependencies, limitations, and risks are documented.<br>
  - The implementation effort is estimated.<br>
  - The findings are reviewed by the development team and used to refine US24.
</p>


##### **SP04 - Investigate Monitoring Trend Visualization Options**

<p style="text-align: justify;">
  <b>Context:</b> SafeLab includes alert, temperature, and humidity trend analysis through US48 - View alert trends, US49 - View temperature trends, and US50 - View humidity trends. These functionalities use historical monitoring information to represent changes over time. Before implementing the trend visualizations in the mobile applications, the development team needs to evaluate compatible visualization alternatives and validate how SafeLab historical monitoring data can be represented.
</p>

<p style="text-align: justify;">
  <b>Spike Story:</b><br>
  As a Development Team,<br>
  I want to investigate and prototype visualization alternatives for SafeLab monitoring trends,<br>
  so we can select an appropriate approach for representing alert, temperature, and humidity historical information before implementing US48, US49, and US50.
</p>

<p style="text-align: justify;">
  <b>Acceptance Criteria:</b>
</p>

<p style="text-align: justify;">
  <b>Scenario 1: Visualization alternatives are investigated</b><br>
  <b>Given</b> that SafeLab needs to represent historical alert, temperature, and humidity information<br>
  <b>When</b> the developer investigates visualization alternatives compatible with the mobile solution<br>
  <b>Then</b> the available alternatives and their main characteristics are documented.
</p>

<p style="text-align: justify;">
  <b>Scenario 2: Native mobile compatibility is evaluated</b><br>
  <b>Given</b> that SafeLab must include a native mobile application<br>
  <b>When</b> the developer evaluates the candidate visualization alternatives<br>
  <b>Then</b> their compatibility and integration requirements for the native implementation are documented.
</p>

<p style="text-align: justify;">
  <b>Scenario 3: Cross-platform compatibility is evaluated</b><br>
  <b>Given</b> that SafeLab must include a cross-platform mobile application<br>
  <b>When</b> the developer evaluates the candidate visualization alternatives<br>
  <b>Then</b> their compatibility and integration requirements for the cross-platform implementation are documented.
</p>

<p style="text-align: justify;">
  <b>Scenario 4: SafeLab historical data is evaluated</b><br>
  <b>Given</b> that SafeLab stores historical information related to alerts, temperature, and humidity<br>
  <b>When</b> the developer analyzes the data required by the trend functionalities<br>
  <b>Then</b> the information required for the visualization prototype is documented.
</p>

<p style="text-align: justify;">
  <b>Scenario 5: Temperature trend visualization is prototyped</b><br>
  <b>Given</b> that historical temperature data is available for technical validation<br>
  <b>When</b> the developer uses the selected visualization alternative<br>
  <b>Then</b> the prototype represents the temperature information across the evaluated period.
</p>

<p style="text-align: justify;">
  <b>Scenario 6: Humidity and alert trend visualization is validated</b><br>
  <b>Given</b> that historical humidity and alert information is available for technical validation<br>
  <b>When</b> the developer uses the selected visualization alternative<br>
  <b>Then</b> the prototype verifies that the required historical information can also be represented.
</p>

<p style="text-align: justify;">
  <b>Scenario 7: Implementation effort is estimated</b><br>
  <b>Given</b> that the candidate visualization alternatives have been evaluated<br>
  <b>When</b> the development team compares their implementation requirements<br>
  <b>Then</b> the main implementation tasks and approximate effort are documented.
</p>

<p style="text-align: justify;">
  <b>Scenario 8: Findings are documented and reviewed</b><br>
  <b>Given</b> that the visualization prototype has been evaluated<br>
  <b>When</b> the development team reviews the results<br>
  <b>Then</b> the selected approach, requirements, limitations, and implementation considerations are documented for the refinement of US48, US49, and US50.
</p>

<p style="text-align: justify;">
  <b>Definition of Done:</b><br>
  - Compatible visualization alternatives are evaluated.<br>
  - Native and cross-platform integration requirements are documented.<br>
  - The historical information required for the prototype is identified.<br>
  - A minimal trend visualization prototype is completed.<br>
  - Temperature, humidity, and alert information can be represented in the technical validation.<br>
  - The implementation effort is estimated.<br>
  - The findings are reviewed by the development team and used to refine US48, US49, and US50.
</p>

### **2.4.2. Impact Mapping**
### **2.4.3. Product Backlog**
## **2.5. Strategic-Level Domain-Driven Design**
### **2.5.1. Event Storming**
#### **2.5.1.1. Candidate Context Discovery**
#### **2.5.1.2. Domain Message Flows Modeling**
#### **2.5.1.3. Bounded Context Canvases**
### **2.5.2. Context Mapping**
### **2.5.3. Software Architecture**
#### **2.5.3.1. Software Architecture Context Level Diagrams**
#### **2.5.3.2. Software Architecture Container Level Diagrams**
#### **2.5.3.3. Software Architecture Deployment Diagrams**
## **2.6. Tactical-Level Domain-Driven Design**
### **2.6.x. Bounded Context: <Bounded Context Name>**
#### **2.6.x.1. Domain Layer**
#### **2.6.x.2. Interface Layer**
#### **2.6.x.3. Application Layer**
#### **2.6.x.4 Infrastructure Layer**
#### **2.6.x.5. Bounded Context Software Architecture Component Level Diagrams**
#### **2.6.x.6. Bounded Context Software Architecture Code Level Diagrams**
##### **2.6.x.6.1. Bounded Context Domain Layer Class Diagrams**
##### **2.6.x.6.2. Bounded Context Database Design Diagram**
