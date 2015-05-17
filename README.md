# IBridgePy

                             tradingwithIB.com
IBridgePy is a flexiable and easy-to-use Python package which talks to Interactive Brokers C++ API. Different from Ibpy, which is a third-party implementation of the API used for accessing the Interactive Brokers (IB) on-line trading system that, IBridgePy does not re-implement the API of IB. It only makes a wrapper around IB’s C++ API so that Python can call the C++ API directly. Because IB’s C++ API is an officially maintained by IB, it is unlikely to have unexpected program errors and will be upgraded whenever IB has a new release of its trading system. Because IBridgePy is built on IB’s official C++ API, the users can easily refer to IB’s documentation for each function’s signature and usage. 

IBridgePy is also a completely open source software and has two main parts. One is a Python library which includes a lot of API functions similar to Quantopian’s interface. This makes it easy for users to build algorithmic trading strategies if they are familiar with Quantopian. This part of the source code can be found in Github/IBridgePy/IBridgePy_Main_Repo. The Python wrapper for the IB C++ API is also open source and the source code can be found in Github/IBridgePy/IBridgePy_cpp_src.

IBirdgePy can be used at different operating systems, including Microsoft Windows, Mac, Linux-Ubuntu, Linux-CentOS. You can find the IBCpp files in Github/IBridgePy/IBridgePy_IBCpp_diff_sys.

tradingwithIB.com/instruction :The instructions for installing and using IBridgePy

tradingwithIB.com/community :At the community, we talk about how to use IBridgePy to run algo trading strategies.

-----------------------------------------------------
If you want to have a quick start, please go to folder simple_examples
You will find 3 examples in the folder:

        Request_historical_data.py
You can use this code to request historical data from IB, following IB’s restrictions.

        Request_real_time_quotes.py
You can use this code to request real time quotes from IB as long as you have the permission from IB. You may need to pay monthly fee to purchase real time data. IB’s pricing is very competitive.

        Place_order.py
This one is to place a market order or a limit order to buy/sell some shares of a security. The coding allows you to purchase stock, forex and futures.

To run these simple examples, you can just run the file as long as you have added the IBridgePy local folder to the PYTHONPATH.

For detailed installation instruction, please visit tradingwithIB.com
-------------------------------------------------------

