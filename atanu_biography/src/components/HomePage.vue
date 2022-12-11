<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Bio</template>

    Experienced Senior Software Engineer with a demonstrated history of working in the information technology and
    services industry. Skilled in Java, J2EE, Spring, Spring Boot, REST, SOAP, Microservices, Kafka, Drools, Hibernate,
    JSF, HTML5, CSS, Javascript, VueJS, NodeJS, PHP, PL/SQL, MongoDB, AWS. Currently working as Associate Software
    Engineer at J.P. Morgan
    & Chase Bank having a total work experience of more than 12 years. My main area of experience is in working as a
    full stack Java application developer as well as managing my team to ensure delivery of projects on time. I have got
    good analytical skills and problem-solving abilities. I also possess great enthusiasm for learning new things.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Tooling</template>

   I have good hands on experience with: 
    <ul>
      <li><a href="https://aws.amazon.com/">AWS</a></li>
      <li><a href="https://www.terraform.io/">Terraform</a></li>      
      <li>Java and Web Development with IDEs such as :</li>
      <ul>
        <li>
          <a href="https://www.jetbrains.com/idea/">IntelliJ IDEA</a>
        </li>
        <li>
          <a href="https://eclipseide.org/">Eclipse</a>
        </li>
        <li>
          <a href="https://spring.io/tools">Spring Tool Suite</a>
        </li>
        <li>
          <a href="https://www.jetbrains.com/webstorm/">WebStorm</a>
        </li>
        <li>
          <a href="https://code.visualstudio.com/">Visual Studio Code</a>
        </li>  
      </ul>
      <li>Java Web and Application Servers such as :</li>
      <ul>
        <li>
          <a href="https://tomcat.apache.org/">Apache Tomcat</a>
        </li>
        <li>
          <a href="https://www.wildfly.org/">WildFly</a>
        </li>
        <li>
          <a href="https://www.ibm.com/products/websphere-application-server">Websphere</a>
        </li>
      </ul>
      <li>API Management and Integration :</li>
      <ul>
        <li>
          <a href="https://cloud.google.com/apigee">Google Apigee</a>
        </li>
        <li>
          <a href="https://wso2.com/api-manager/">WSO2 API Manager</a>
        </li>        
      </ul>
      <li>API Building and Testing Tools :</li>
      <ul>
        <li>
          <a href="https://www.postman.com/">Postman</a>
        </li>
        <li>
          <a href="https://www.soapui.org/">SoapUI</a>
        </li>        
      </ul>
      <li>Database Design, Development, Integration and ETL :</li>
      <ul>
        <li>
          <a href="https://www.oracle.com/database/sqldeveloper/SQL Server">SQL Developer</a>
        </li>
        <li>
          <a href="https://www.quest.com/toad/">Toad</a>
        </li>
        <li>
          <a href="https://www.mongodb.com/products/compass">MongoDB Compass</a>
        </li>
        <li>
          <a href="https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16">SQL Server Management Studio</a>
        </li>
        <li>
          <a href="https://dm-us.informaticacloud.com/identity-service/home">Informatica Cloud</a>
        </li>        
      </ul>
    </ul>


  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Ecosystem</template>

    Get official tools and libraries for your project:
    <a href="https://pinia.vuejs.org/" target="_blank" rel="noopener">Pinia</a>,
    <a href="https://router.vuejs.org/" target="_blank" rel="noopener">Vue Router</a>,
    <a href="https://test-utils.vuejs.org/" target="_blank" rel="noopener">Vue Test Utils</a>, and
    <a href="https://github.com/vuejs/devtools" target="_blank" rel="noopener">Vue Dev Tools</a>. If
    you need more resources, we suggest paying
    <a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">Awesome Vue</a>
    a visit.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Community</template>

    Got stuck? Ask your question on
    <a href="https://chat.vuejs.org" target="_blank" rel="noopener">Vue Land</a>, our official
    Discord server, or
    <a href="https://stackoverflow.com/questions/tagged/vue.js" target="_blank" rel="noopener">StackOverflow</a>. You
    should also subscribe to
    <a href="https://news.vuejs.org" target="_blank" rel="noopener">our mailing list</a> and follow
    the official
    <a href="https://twitter.com/vuejs" target="_blank" rel="noopener">@vuejs</a>
    twitter account for latest news in the Vue world.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Support Vue</template>

    As an independent project, Vue relies on community backing for its sustainability. You can help
    us by
    <a href="https://vuejs.org/sponsor/" target="_blank" rel="noopener">becoming a sponsor</a>.
  </WelcomeItem>
</template>
