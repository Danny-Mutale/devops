flowchart TD
    subgraph WebsiteRedesign
        A1[Visual Appeal]
        A2[Responsive Design]
        A3[Booking System Integration]
    end

    subgraph OnlineActivityReservations
        B1[Activity Catalog]
        B2[Real-Time Availability]
        B3[Cancellation and Modification]
    end

    subgraph DiningReservations
        C1[Restaurant Profiles]
        C2[Table Reservations]
        C3[Menu Customisation]
    end

    subgraph SpaAndWellnessBooking
        D1[Service Listing]
        D2[Appointment Scheduling]
        D3[Membership and Packages]
    end

    subgraph GuestPortal
        E1[Personalised Dashboard]
        E2[Digital Concierge]
    end

    subgraph EventManagement
        F1[Event Planning Services]
        F2[Online Inquiries and Quotes]
    end

    subgraph SocialMediaIntegration
        G1[Social Media Feeds]
        G2[Guest Reviews and Testimonials]
    end

    subgraph SEOandMarketing
        H1[Search Engine Optimisation]
        H2[Email Marketing Integration]
    end

    subgraph MultiLanguageSupport
        I1[Language Options]
        I2[Currency Conversion]
    end

    %% Connections for Main Flow
    WebsiteRedesign --> OnlineActivityReservations
    OnlineActivityReservations --> DiningReservations
    DiningReservations --> SpaAndWellnessBooking
    SpaAndWellnessBooking --> GuestPortal
    GuestPortal --> EventManagement
    EventManagement --> SocialMediaIntegration
    SocialMediaIntegration --> SEOandMarketing
    SEOandMarketing --> MultiLanguageSupport

    %% Additional Deliverables
    Z1[Real-time room booking system] --> WebsiteRedesign
    Z2[Activity booking system] --> OnlineActivityReservations
    Z3[Dining reservation system] --> DiningReservations
    Z4[Spa appointment system] --> SpaAndWellnessBooking
    Z5[Personalised guest portal] --> GuestPortal
    Z6[Event management tool] --> EventManagement
    Z7[SEO and social media integration] --> SocialMediaIntegration
    Z8[Multi-language and currency support] --> MultiLanguageSupport
