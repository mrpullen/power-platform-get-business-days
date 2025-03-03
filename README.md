# Get Federal Business Days Flow - Power Platform

This solution will allow you to specify a start date - and a number of business days and generate the correct due date - in very good time. I had previously used a looping function - to both generate the holiday dates - and count business days - this solution is about 10x faster.

Solution Flows:
 - Activity - GetBusinessDaysDueDate
 - Activity - IsWeekend
 - Activity - IsHoliday


I've left this as unmanaged - that way you can modify the holiday json data - for your specific use case - the default is to list the federal holidays in the US.

[GetBusinessDays Unmanaged](https://github.com/mrpullen/power-platform-get-business-days/blob/main/solution/GetBusinessDays_1_0_0_1.zip)
