A modern, responsive, and customizable portfolio website template designed to showcase personal projects, technical skills,
professional experience, and achievements. Built with a focus on clean design, intuitive navigation,
and a professional user experience, it provides a flexible starting point for developers, designers, freelancers,
and professionals looking to establish their online presence.

Key Features
Clean, modern, and responsive design
Customizable sections for projects, skills, and experience
Intuitive navigation and user-friendly layout
Reusable components and organized code structure
Easy customization to match different personal brands and professional needs

Technology stack
React 19 — component-based user interface.
TypeScript — type-safe application development.
Vite — fast local development and production builds.
Tailwind CSS 4 — utility-first styling and responsive design.
Wouter — lightweight client-side routing.
Lucide React — consistent interface icons.
shadcn/ui and Radix UI — reusable accessible UI primitives. 
Framer Motion — motion-ready dependency for future interactions.
pnpm — dependency installation and project scripts.

Purpose: A reusable portfolio template that simplifies the process of building a professional online presence.

Accessibility and responsive design
The interface uses semantic sections, accessible navigation labels, visible keyboard focus 
states, responsive breakpoints, and reduced-motion considerations. You should still test 
your own content on mobile and desktop widths, check color contrast, verify image 
alternative text, and confirm that every interactive element is reachable with a keyboard

Customize the portfolio

Most personal content is centralized near the top of:
client/src/pages/Home.tsx
Look for the 
content object and replace the example information with your own.

Personal information
Update  content.person with your name, role, location, email address, introduction, and 
availability.
person: {
name: "Your Name",
role: "Your role or specialty",
location: "Based in Your City · Working globally",
email: "hello@yourdomain.com",
intro: "A short explanation of what you do and the value you create.",
availability: "Available for selected projects · 2026",
},

About section
Edit content.about to describe your background, approach, experience, and current 
interests.

Skills section
Replace the sample skills with your actual services or capabilities. Keep the descriptions 
short and specific.
skills: [
{ label: "Product design", detail: "Research · UX · prototyping" },
{ label: "Front-end development", detail: "React · TypeScript · accessibility
{ label: "Brand systems", detail: "Identity · direction · guidelines" },
],


Projects section
Update content.projects with your own case studies, project names, categories, 
descriptions, tags, and images.
{
},
number: "01",
title: "Your project title",
category: "Product design · 2026",
description: "Explain the problem, your contribution, and the result in one co
image: "/your-project-image.jpg",
tags: ["Strategy", "UX / UI", "Development"],
Strong project descriptions answer three questions:
1. What problem needed to be solved?
2. What did you contribute?
3. What changed because of the work?

   
Author: Christelle Nasr

