# CS230_OperatingPlatforms
Summary of the Client and Software Requirements

The client, The Gaming Room, requested the expansion of their Android game Draw It or Lose It into a fully distributed, web-based application. The new system needed to support cross-platform compatibility across Windows, macOS, Linux, iOS, and Android, allowing multiple teams and players to compete simultaneously. Key requirements included unique identifiers for every game, team, and player, enforcement of unique names, a singleton game service to manage sessions, and secure communication between clients and servers. The goal was to deliver a scalable, secure, and cost-effective architecture that could grow with the company’s future needs.

What I Did Well

I did especially well in the organization and clarity of the design document. Each section—requirements, constraints, domain model, and recommendations—was presented with clear logic and professional formatting. I successfully integrated object-oriented design principles like inheritance, encapsulation, and polymorphism while explaining their role in the system. I also demonstrated a strong understanding of distributed systems, recommending Linux hosting and a multi-tier architecture for scalability and cost savings.

Helpful Parts of the Design Process

Working through the design document before coding made me appreciate how essential planning and architecture are in software development. Defining requirements, constraints, and class relationships early on reduced ambiguity and provided a solid blueprint for implementation. This process also highlighted how design decisions—like using a singleton pattern or RESTful APIs—affect both performance and scalability in real-world systems.

Potential Revisions

If I could revise one part of my document, I would expand the security section even more. While I covered encryption, authentication, and authorization standards, I could improve it by detailing how to implement OAuth 2.0 for player authentication and showing sample flow diagrams. Adding more technical depth would help developers and stakeholders better visualize how user data stays protected.

Interpreting and Implementing User Needs

I interpreted the client’s needs by focusing on user experience and accessibility. Players needed a responsive interface that worked on any device, so I proposed using HTML5 with Java-based backend logic. I also recognized the need for reliability, so I included features like load balancing, redundancy, and secure HTTPS connections. Considering user needs ensured the system would be intuitive, fast, and fair for all players—something critical in gaming environments.

Approach to Software Design

My design approach followed object-oriented analysis and design (OOAD) combined with a layered architecture strategy. I first modeled the domain with UML to clarify entity relationships (Game, Team, Player, GameService) and then proposed the technical infrastructure to support it. In future projects, I plan to use automated modeling tools, version-controlled design documents, and continuous integration testing to streamline development and maintain alignment between design and code.
