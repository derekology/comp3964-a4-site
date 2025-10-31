<template>
  <div class="max-w-3xl mx-auto p-6 font-sans text-gray-800">
    <h1 class="text-5xl tracking-widest font-semibold mb-2 uppercase pb-3">Derek Woo</h1>
    <p class="text-md mb-6">
      Cloud developer and marketer with experience building technical systems across software, automation,
      and business operations.
      Focused on backend engineering, AWS development, and data pipelines.
      Proven ability to scope and translate business initiatives to deliver impactful technical solutions.
    </p>

    <ResumeSection title="Core Competencies">
      <p>
        <strong>Cloud & Infrastructure:</strong> Deployments on AWS (EC2, EKS, Lambda); Docker & Kubernetes; Ansible;
        Jenkins<br>
        <strong>Backend & APIs:</strong> RESTful/serverless services (Python/Flask, TypeScript/Node, Express, GraphQL,
        RabbitMQ)<br>
        <strong>Data:</strong> ETL automation (Kafka, Cassandra, Pandas); DB dev (ClickHouse, PostgreSQL, SQL Server,
        SQLAlchemy)<br>
        <strong>Monitoring & Analytics:</strong> Observability pipelines and dashboards (Prometheus, Grafana, Superset,
        K6)<br>
        <strong>Frontend & Applications:</strong> Interactive web and desktop apps (TypeScript/JavaScript, React, Vue,
        Python, PyQT)<br>
        <strong>Other:</strong> General automation (Python/Bash scripts); Azure AI Engineer & Fundamentals Certificates;
        Linux; Git
      </p>
    </ResumeSection>

    <ResumeSection title="Education">
      <p>
        <strong>British Columbia Institute of Technology:</strong> Computer Systems Technology (Cloud Development) —
        2023–2025<br>
        <strong>Simon Fraser University:</strong> Bachelor of Business Administration (Marketing & Human Resources) —
        2013–2018
      </p>
    </ResumeSection>

    <ResumeSection title="Experience">
      <div class="space-y-4">
        <div>
          <h3 class="font-semibold">Software Engineer (Co-op) @ Netskrt</h3>
          <p class="italic text-sm mb-1">Jan – Dec 2024 | Python, PostgreSQL, Kubernetes, RabbitMQ, Ansible</p>
          <ul class="list-disc list-inside">
            <li>Built internal service API to manage edge system settings, reducing support tickets by 20%</li>
            <li>Conducted load testing with Kafka + K6 to define throughput limits on deployed infrastructure</li>
            <li>Implemented dynamic attribute ingestion in Scrapy pipelines to improve schema flexibility</li>
            <li>Reduced operational monitoring time by 10+ hours/week via internal status aggregator</li>
          </ul>
        </div>
        <div>
          <h3 class="font-semibold">Business Technology Consultant @ CaseMogul</h3>
          <p class="italic text-sm mb-1">Jan 2021 – May 2024 | Python, JavaScript, Selenium, Pandas</p>
          <ul class="list-disc list-inside">
            <li>Automated ETL pipelines to move data accurately and efficiently</li>
            <li>Reduced manual work by 12+ hours/week through scripts, scrapers, and batch jobs</li>
          </ul>
        </div>
        <div>
          <h3 class="font-semibold">Marketing Automation Specialist @ Ceridian Dayforce</h3>
          <p class="italic text-sm mb-1">Feb 2022 – May 2023 | Python, JavaScript</p>
          <ul class="list-disc list-inside">
            <li>Consolidated nurture systems into a scalable analytics-focused program for 500k+ leads</li>
            <li>Built dynamic workflows for syndicated campaigns</li>
          </ul>
        </div>
      </div>
    </ResumeSection>

    <ResumeSection title="Projects">
      <div class="space-y-4">
        <div>
          <h3 class="font-semibold">Netskrt Edge Explorer</h3>
          <p class="italic text-sm mb-1">JavaScript, Python, Helm, Kubernetes, Docker, ArgoCD</p>
          <ul class="list-disc list-inside">
            <li>Consolidated live data from Zabbix and APIs to monitor 170+ nodes</li>
            <li>Containerized and deployed via Helm/ArgoCD on Kubernetes</li>
          </ul>
        </div>
        <div>
          <h3 class="font-semibold">Relguessr</h3>
          <p class="italic text-sm mb-1">Vue, Node.js, Python, MongoDB, AWS Lambda</p>
          <ul class="list-disc list-inside">
            <li>Full-stack app where users guess real estate prices on an interactive map</li>
            <li>Scraped, summarized, and geocoded property data into a serverless backend API</li>
          </ul>
        </div>
      </div>
    </ResumeSection>
  </div>
</template>

<script setup>
import ResumeSection from './components/ResumeSection.vue'
</script>
