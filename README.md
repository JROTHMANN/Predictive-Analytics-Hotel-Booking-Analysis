



# Run this cell to display the README template — then copy the printed output

readme_template = '''
# Predicting Hotel Booking Cancellations: Protecting Revenue with Data

**One-line hook:** Analyzing how to predict hotel booking cancellations and help hotels reduce revenue loss from empty rooms.

---

## The Business Problem

Hotels frequently face last-minute booking cancellations that result in empty rooms and lost revenue. Without early warning signals, hotel managers struggle to adjust staffing, pricing, or overbooking strategies. By predicting which bookings are most likely to cancel, hotels can take proactive actions that protect revenue and improve operational planning.

## The Data

This analysis uses a publicly available dataset of 119,390 hotel bookings from a Portuguese resort and city hotel between 2015 and 2017. Each record captures information about guest booking behavior, including how far in advance they booked, the type of deposit made, the number of guests, and the booking channel used. These factors allow us to analyze patterns in customer behavior and identify which reservations are most likely to be cancelled.

## Key Discoveries

- **Guests who book far in advance cancel more often:** Bookings made months ahead show significantly higher cancellation rates than last-minute reservations.
- **Deposit policies strongly influence cancellations:** Bookings without deposits cancel far more frequently than those with deposits.
- **Repeat guests are much more reliable:** Returning customers cancel significantly less often than first-time guests.
- **Customers who make special requests cancel less frequently:** Guests who personalize their booking are typically more committed to their stay.

## Visualizing the Story

![Cancellation Rate by Deposit Type](cancellation_by_deposit.png)

*Bookings with no deposit have dramatically higher cancellation rates, suggesting deposit policies could significantly reduce lost revenue.*

## Prediction Model

A predictive model was built to identify bookings at risk of cancellation. The baseline Gaussian Naive Bayes model achieved about 76% accuracy, while Decision Tree and Logistic Regression models improved performance to around 80%. In practical terms, this means the hotel could correctly identify roughly 8 out of every 10 cancellations before they occur, allowing staff to intervene earlier.

## Recommendations

1. **Require deposits for high-risk bookings:** Our analysis shows bookings without deposits cancel far more frequently. Requiring deposits for certain bookings could reduce cancellations by an estimated 10–15%.
2. **Send automated reminders for early bookings:** Guests who book far in advance cancel more often. Automated confirmation reminders could help reduce uncertainty and recover hundreds of room nights annually.
3. **Encourage repeat guests through loyalty programs:** Repeat guests cancel far less frequently. Increasing repeat bookings by even 5–10% could improve occupancy stability.

## Tools & Techniques

Python | Pandas | Scikit-Learn | Matplotlib | Seaborn | Gaussian Naive Bayes | Decision Tree | Logistic Regression | Google Colab

---

*This project was completed as part of ISOM 835: Predictive Analytics at Suffolk University's Sawyer Business School.*
'''

print(readme_template)
