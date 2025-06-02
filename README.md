# Z-score-Probability-Indicator-with-Hull-Moving-Average-for-Trading-View
This indicator is a modified version of SteverSteves's original work, enhanced by Erika Barker. It visually represents asset price movements in terms of standard deviations from a Hull Moving Average (HMA), commonly known as a Z-Score.

NOTE: To use, you don't need to do anything here with this source code.  Simply go to Trading View, Open Charts, Add Indicator, and Search for the Z-Score Probability Indicator with HMA

This is Version 2 of the Z-Score Probability Indicator (HMA) by Erika Barker.
Version 1 of this indicator was a heavy modification of SteverSteves' Z-score probability indicator, but I've significantly enhanced version 2 of this Z-score indicator with several professional trading features and UX improvements, while maintaining the core concept of measuring price deviations from a Hull Moving Average in terms of standard deviations.

Technical Enhancements

Adaptive Lookback Periods

Dynamically adjusts the lookback length based on market volatility
Uses longer periods in high volatility (for stability) and shorter in low volatility (for responsiveness)
Configurable minimum and maximum boundaries to prevent extreme values
Visual indicator shows the current adaptive period length



Divergence Detection System

Identifies when price makes a new high/low but the Z-Score fails to confirm
Uses a sophisticated pivot detection algorithm to reduce false signals
Configurable sensitivity threshold
Visual markers for both bullish and bearish divergences



Improved Error Handling

Protected against division by zero in standard deviation calculations
Added checks for NaN values and the first few bars where data is insufficient
More robust pivot detection to reduce false signals



Performance Optimization

Conditional calculations that only run when features are enabled
Better variable management to reduce unnecessary recalculations
More efficient code structure



User Interface Improvements

Organized Settings Menu

Settings grouped into logical categories for easier navigation
Added tooltips for better explanation of each option
Improved defaults for better out-of-the-box experience



Modernized Visual Design

Professional color scheme with Material Design-inspired colors
Customizable color settings for all visual elements
Improved contrast and readability
Enhanced probability zone visualization



Interactive Information Display

Improved Z-Score probability table with current value indicator
Clear mode indicator (Adaptive vs Fixed)
Better positioning of price level labels



Custom Alerts

Added alerts for bullish and bearish divergences
Added alerts for crossing extreme Z-Score thresholds
Custom alert messages with relevant trading information




Code Structure Improvements

Updated to Pine Script v6

Leverages the latest Pine Script features and optimizations


Better Variable Organization

Clearer variable naming conventions
More logical grouping of related calculations
Improved comments for better code maintainability



Fixed Syntax Issues

Corrected issues with multi-line function calls
Fixed variable scope problems
Added proper conditional processing




Usage Recommendations
This enhanced Z-Score indicator is particularly effective for:

Mean-reversion trading strategies
Identifying potential reversal points
Statistical analysis of price movements
Volatility-aware market analysis


For best results, combine with volume analysis and trend identification tools. The divergence detection is especially useful for finding high-probability reversal points in ranging markets.

