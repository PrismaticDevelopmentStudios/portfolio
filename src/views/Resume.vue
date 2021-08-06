<template>
  <div class="main">
    <div class="line1">Matthew Brignola</div>
    <div class="line1 link">
      <a
        href="mailto:matthewbrignola@ymail.com"
        title="Click to send me an email"
        >matthewbrignola@ymail.com</a
      >
    </div>
    <div class="line1">719-351-5828</div>
    <table>
      <p class="large">Work Experience</p>
      <tr>
        <td>
          <ul>
            <p>
              Managed Services Consultant<br />
              for Enterprise Content Management (OPENTEXT Content Server
              Software)
            </p>
            <p>AppTier LLC in Denver, CO</p>
            <p>April 2019-October 2019</p>
            <li>
              Installation and management of software a Windows Server and
              application software
            </li>
            <li>Installation and management of Apache web server</li>
            <li>Installation of Win32 database</li>
            <li>
              Generation of weekly data usage reports and delivery of reports to
              our clients
            </li>
            <li>
              Use of OPENTEXT documentation to assist in triage and
              troubleshooting while resolving tickets
            </li>
            <li>
              Use of Manage Engine managed services ticketing system software to
              document, triage, and resolve tickets
            </li>
          </ul>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <p>CEO and Founder</p>
            <p>The Brink Media LLC in Denver, CO</p>
            <p>April 2017-October 2019</p>
            <li>
              Video, Web Design, Graphic Design, and Digital Marketing Services
            </li>
            <li>
              Management of Design, Marketing and Sales, and Core Business
              Operations
            </li>
            <li>Management of Company Officers and Other Personnel</li>
            <li>Meeting Scheduling and Facilitation</li>
            <li>Financial Reports and Projections</li>
          </ul>
        </td>
      </tr>
      <tr>
        <td>
          <ul>
            <p>Career and Technology Educator</p>
            <p>Denver Public Schools in Denver, CO</p>
            <p>June 2014 - April 2018</p>
            <li>
              Career Technology Teacher at Noel Community Arts School Middle
              School (2017-2018)
            </li>
            <li>Maintenance and setup of iMac computer lab</li>
            <li>WAN connectivity</li>
            <li>Meeting Scheduling and Facilitation</li>
            <li>
              FSetup and Maintenance of AV equipment (cameras, monitors,
              lighting equipment, Adobe, etc.)
            </li>
          </ul>
        </td>
      </tr>
    </table>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.line1 {
  margin: 1%;
  font-family: "Courier New", Courier, monospace;
  font-size: 1.5em;
  font-weight: 600;
}

table {
  margin-left: auto;
  margin-right: auto;
  width: 80%;
  background: white;
  padding: 5%;
  border-radius: 15px;
  box-shadow: 1px 2px 3px rgb(0, 0, 0, 0.5);
}
td {
  padding: 1%;
}
ul {
  margin: 0;
  padding: 0;
  text-align: left;
}
p {
  margin: 0;
  padding: 0;
  font-size: 1em;
  font-weight: 600;
}
.large {
  font-size: 2em;
}
.link {
  text-decoration: underline;
}
</style>