# Copyright (c) 2020 vesoft inc. All rights reserved.
#
# This source code is licensed under Apache 2.0 License,
# attached with Common Clause Condition 1.0, found in the LICENSES directory.

nebula_add_library(
    function_manager_obj OBJECT
    FunctionManager.cpp
)

nebula_add_library(
    agg_function_obj OBJECT
    AggregateFunction.cpp
)

nebula_add_library(
    time_function_obj OBJECT
    TimeFunction.cpp
)

nebula_add_subdirectory(test)
