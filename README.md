<body>
    <h1>Airbnb Dataset Analysis Project</h1>
    <p>This project delves into the comprehensive analysis of the Airbnb market in Clark County, Nevada, utilizing the Inside Airbnb dataset. Aimed at uncovering the intricacies of pricing, location, and room types, this analysis seeks to provide actionable insights for potential investors and hosts within the Airbnb ecosystem. By examining various aspects of the dataset, including neighborhood distribution, price variations by room type, and the impact of reviews and availability on pricing, this project offers a detailed exploration of the factors influencing Airbnb listings.</p>
    <i>Created and presented as a final project for CS 489 - "Advanced Topics in Computer Science" at UNLV. This project recieved an A grade, and the accompanying presentation is also included as a PDF file.</i>
    <h2>Project Overview</h2>
    <h3>Origin and Motivation</h3>
    <ul>
        <li>Data Source: The project leverages data from Inside Airbnb, an initiative started in 2016 to analyze Airbnb’s impact on communities.</li>
        <li>Purpose: To investigate whether the Inside Airbnb Dataset can facilitate more educated investment decisions in the Airbnb market, specifically focusing on the Clark County area.</li>
    </ul>
    <h2>Dataset Highlights and Hypothesis Testing</h2>
    <p>This project utilizes the Inside Airbnb dataset to analyze the Airbnb market in Las Vegas, focusing on variables such as neighborhood, geographical coordinates, room types, pricing, minimum stay requirements, number of reviews, and annual availability. The dataset encompasses listings in Clark County, NV, offering a rich source for understanding market dynamics in diverse areas, including Boulder City, Henderson, Las Vegas, Mesquite, North Las Vegas, Nellis AFB, and unincorporated regions.</p>
    <h3>Preprocessing Steps:</h3>
    <ul>
        <li><strong>Data Cleaning</strong>: Removed extraneous columns to concentrate on variables directly impacting the Airbnb experience and investment potential.</li>
        <li><strong>Area Distribution</strong>: Analyzed listings across Clark County, categorizing them by urban and suburban locales to ascertain regional market trends.</li>
    </ul>
    <h3>Hypothesis Testing Insights:</h3>
    <ol>
        <li><strong>Review Count vs. Price Hypothesis</strong>:
            <ul>
                <li><em>Initial Hypothesis</em>: More reviews would correlate with higher prices, assuming reviews signal popularity and justify premium pricing.</li>
                <li><em>Outcome</em>: The hypothesis was rejected. Analysis revealed that an increase in reviews typically corresponds to a decrease in price, suggesting that higher-priced properties are rented less frequently, accumulating fewer reviews over time.</li>
            </ul>
        </li>
        <li><strong>Availability vs. Price Hypothesis</strong>:
            <ul>
                <li><em>Initial Hypothesis</em>: Greater availability would indicate higher demand, allowing for increased pricing.</li>
                <li><em>Outcome</em>: This hypothesis was also rejected. Findings indicated a slight negative correlation, where properties with more availability tended to have lower prices, possibly due to their ability to generate consistent revenue, reducing the need for higher individual booking costs.</li>
            </ul>
        </li>
        <li><strong>Minimum Nights vs. Price Hypothesis</strong>:
            <ul>
                <li><em>Initial Hypothesis</em>: Listings requiring longer minimum stays could afford to charge less per night due to reduced operational costs associated with guest turnover.</li>
                <li><em>Outcome</em>: The hypothesis was accepted. Data showed that as the minimum required nights increase, the price per night decreases, aligning with the premise that lower turnover costs enable more competitive pricing.</li>
            </ul>
        </li>
    </ol>
    <h2>Conclusions and Implications</h2>
    <p>The project's findings challenge common assumptions about pricing strategies in the Airbnb market, providing nuanced insights into how reviews, availability, and minimum stay requirements can influence listing prices. These insights are invaluable for new and existing hosts aiming to optimize their pricing strategies and for investors considering entering the Airbnb market.</p>
    <h2>Technologies Used</h2>
    <ul>
        <li><strong>Data Analysis</strong>: Pandas for data manipulation, Matplotlib and Seaborn for visualization.</li>
        <li><strong>Statistical Analysis</strong>: Scipy for advanced statistical analysis.</li>
    </ul>
    <h2>Significance</h2>
    <p>This analysis not only sheds light on the dynamic nature of the Airbnb marketplace in Clark County but also emphasizes the importance of data-driven decision-making for hosts and investors. By revealing unexpected patterns and correlations, it encourages further exploration and hypothesis testing in the realm of short-term rental investments.</p>
    <h2>Future Directions</h2>
    <p>Encouraged by the findings, future work could expand to other regions, incorporate more sophisticated machine learning models for prediction, and explore additional variables that could impact Airbnb listing success.</p>
</body>
