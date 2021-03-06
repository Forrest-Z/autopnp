#
# Copyright (c) 2011-2014, fortiss GmbH.
# Licensed under the Apache License, Version 2.0.
# 
# Use, modification and distribution are subject to the terms specified
# in the accompanying license file LICENSE.txt located at the root directory
# of this software distribution. A copy is available at
# http://chromosome.fortiss.org/.
#
# This file is part of CHROMOSOME.
#
# $Id: CMakeLists.txt 7575 2014-02-25 08:51:07Z wiesmueller $
#         This file has been generated by the CHROMOSOME Modeling Tool (XMT)
#         (fortiss GmbH).

# PROTECTED REGION ID(CALCULATOR_ADV_CLIENT_CMAKELISTS_TXT_BEGIN) ENABLED START

# PROTECTED REGION END

xme_add_component (
    "calculator_adv_client"
    HEADERS
        "include/clientComponentWrapper.h"
        "include/clientComponent.h"
        "include/sendRequestFunctionWrapper.h"
        "include/sendRequestFunction.h"
        "include/printResponseFunctionWrapper.h"
        "include/printResponseFunction.h"
        "include/clientManifest.h"
    SOURCES
        "src/clientComponentWrapper.c"
        "src/clientComponent.c"
        "src/sendRequestFunctionWrapper.c"
        "src/sendRequestFunction.c"
        "src/printResponseFunctionWrapper.c"
        "src/printResponseFunction.c"
        "src/clientManifest.c"
    DEPENDS
        xme_core_directory_attribute
    # PROTECTED REGION ID(CALCULATOR_ADV_CLIENT_CMAKELISTS_TXT_XMEADDCOMPONENT) ENABLED START

    # PROTECTED REGION END
)

# PROTECTED REGION ID(CALCULATOR_ADV_CLIENT_CMAKELISTS_TXT_END) ENABLED START

# PROTECTED REGION END
