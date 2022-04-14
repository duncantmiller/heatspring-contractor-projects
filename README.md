# HeatSpring Contractor Projects

I'm looking for contractors who can help me with a few projects we have been working on in our online learning platform web app called [HeatSpring](https://heatspring.com).

The app is over 10 years old but has been keep pretty up to date and recently underwent a large upgrade, our current stack is:
- Rails 7.0
- Ruby 3.1
- Hotwire
- TailwindCSS
- StimulusJS
- Turbo
- Postgres
- RSpec

We have recently merged in the [JumpstartPro](https://jumpstartrails.com/) template functionality to our app with the help of [Chris Oliver](https://excid3.com/). There are a few additional features we want to add and some additional restructuring we need help with. At the same time, we have also begun to implement a redesign of the front end using TailwindCSS and migrate away from our existing CSS. Chris will continue to be involved but will act more as a consultant and adviser for high level architecture questions in the next phases of our plans.

### Projects
There are two main project categories I need help with:

#### Redesign Projects:

All these related to implementing high fidelity wireframes from our designer [Felix Meens](https://www.felixmeens.com/) using TailwindCSS (designs delivered in a Figma file and Tailwind oriented). We already have tailwind set up in the app have designs for our 3 main marketing pages 95% implemented in tailwind by Chris. We are using both Tailwind and our old CSS with some minor cosmetic updates (fonts, colors etc) so while to goal is to fully migrate to Tailwind we have the ability to migrate pages individually. Most of the pages will be custom designed but we will also be using some TailwindUI especially as we move more towards admin pages.

- Complete the remaining 5% of tweaks left on the the first batch of pages. 
- Implement a second batch of pages focused on our classroom and account that Felix is nearly done designing.
- Implement a third batch related to other marketing pages and instructor admin pages that have not yet been designed. 
- Help setting up good patterns for when to use components, partials or ViewComponents etc along the way. As well as general help in organizing and structuring tailwind related code as we continue to add to it.

#### App + JumpstartPro Projects:

- refactor our existing admin routing which uses the [routing-filter gem](https://github.com/svenfuchs/routing-filter) and custom filters. We'd like to remove the gem and rework how admin access works. I don't think we want to migrate to administrate like JSP since we already have the admin pages built out, but instead implement a similar concept of nested routes and controllers for admin views. Some of the views (particularly in the classroom) currently are the same for both admins and non-admins and we have a lot of conditional statements around content and buttons based on access level. So we'd like to move towards seperating those out into different controllers and managing permissions at the controller level.
- migrate our existing notification system to JumpstartPro notifications + [noticed gem](https://github.com/excid3/noticed)
- migrate our existing checkout process with Stripe to JumpstartPro checkout + [pay gem](https://github.com/pay-rails/pay)
- migrate our existing subscriptions with Stripe to JumpstartPro subscriptions + [pay gem](https://github.com/pay-rails/pay)
- help *hotwireize* our app by adding new front-end features and modernizing existing features using Turbo, StimulusJS and Hotwire.

## Who we are looking for

- Experience with TailwindCSS and implementing wireframes from a designer in Rails
- Able to help set up a solid organized system for Tailwind as we continue to build it out
- Experience with the JumpstartPro template
- A solid understanding of Hotwire, Turbo and StimulusJS and an interest in learning and developing best practices around those as they continue to evolve
- Cares about TDD and code maintainability and can think in terms of a small team capacity
- Responsive and will follow through on commitments, we don’t have any hard deadlines but we are eager to make these changes

## About HeatSpring

HeatSpring provides highly technical online training towards credentialing and certification for professionals in industries addressing the climate crisis like solar, energy storage, geothermal, drones and green building. We help industry experts make money by sharing their knowledge with engineers, electricians, business owners, contractors, designers and installers. Students get access to great content and pathways to earn and maintain respected industry credentials and certifications. We have been in business since 2007 in our niche industries. We are a tiny core team partnering with a lot of expert instructors that we share revenue with.

## Why you should want to work with us

We are an easy going, flexible and positive team, our customers love us, and we help share knowledge that will make the world better.

Feel free to email me directly at duncan@heatspring.com if you are interested or have any questions. I'm HeatSpring's solo full time developer but I also help run other business functions. I would probably be considered a mid-level developer so I'm ready to help but I need some guidance and examples to go off of and am always looking to learn more.

Thanks for reading!

Duncan Miller  
HeatSpring Co-Founder  
https://heatspring.com/about/  
https://github.com/duncantmiller/  
https://www.linkedin.com/in/duncantmiller/  
