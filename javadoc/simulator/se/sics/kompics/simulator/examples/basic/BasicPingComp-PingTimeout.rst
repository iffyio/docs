.. java:import:: java.util UUID

.. java:import:: org.slf4j Logger

.. java:import:: org.slf4j LoggerFactory

.. java:import:: se.sics.kompics ClassMatchedHandler

.. java:import:: se.sics.kompics ComponentDefinition

.. java:import:: se.sics.kompics Handler

.. java:import:: se.sics.kompics Init

.. java:import:: se.sics.kompics Positive

.. java:import:: se.sics.kompics Start

.. java:import:: se.sics.kompics.network Address

.. java:import:: se.sics.kompics.network Header

.. java:import:: se.sics.kompics.network Network

.. java:import:: se.sics.kompics.network Transport

.. java:import:: se.sics.kompics.simutil.msg ContentMsg

.. java:import:: se.sics.kompics.simutil.msg.impl BasicContentMsg

.. java:import:: se.sics.kompics.simutil.msg.impl BasicHeader

.. java:import:: se.sics.kompics.simutil.identifiable Identifiable

.. java:import:: se.sics.kompics.timer CancelPeriodicTimeout

.. java:import:: se.sics.kompics.timer SchedulePeriodicTimeout

.. java:import:: se.sics.kompics.timer Timeout

.. java:import:: se.sics.kompics.timer Timer

BasicPingComp.PingTimeout
=========================

.. java:package:: se.sics.kompics.simulator.examples.basic
   :noindex:

.. java:type:: public static class PingTimeout extends Timeout
   :outertype: BasicPingComp

Constructors
------------
PingTimeout
^^^^^^^^^^^

.. java:constructor:: public PingTimeout(SchedulePeriodicTimeout spt)
   :outertype: BasicPingComp.PingTimeout

